# Docker GDAL2

GDAL2:2.0.1 Docker images.

```bash
docker run --rm -it geographica/gdal2:2.0.1
```

Using a data volume
```bash
$ export DATAFOLDER="-v /folder_with_your_testdata/:/home/datafolder"
$ docker run $DATAFOLDER --name gdal2 -it --rm geographica/gdal2:2.0.1 /bin/bash
```

## Build the image on your own
```bash
$ git clone https://github.com/GeographicaGS/docker-gdal2.git
$ cd docker_gdal2
$ docker build -t geographica/gdal2:2.0.1 .
```

## GDAL 2 info
- https://2015.foss4g-na.org/session/gdal-20-overview
- http://trac.osgeo.org/gdal/wiki/GDAL20Changes

## Credits
- https://github.com/OSGeo/gdal
- https://registry.hub.docker.com/u/geodata/gdal/
