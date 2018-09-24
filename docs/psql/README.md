# Using the `psql` commandline client and other tools


## List the networks. There should be a container running on the network `postgis_default`
```
docker network ls
```

> 2e2afc387fbb        postgis_default               bridge              local


## Connect to PostGIS using the `psql` client (from Docker):

```
docker run --net postgis_default -it --rm \
    --link postgis:postgis postgres psql -h postgis -U postgres -d gis
```

## Using a local client:
```
psql -h localhost -U postgres -d gis
```

## List Tables:

```
\dt
```

## Run SQL Queries:

```
-- Events created by ABC, in descending order of creation date:
SELECT county, quaternary, slope_type, bedrock_ty, land_use_c, creationda, creator
    FROM public."Landslide_Events"
    WHERE creator = 'ABC' ORDER BY creationda DESC;
```

