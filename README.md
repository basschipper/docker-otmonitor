# Docker OpenTherm Monitor

## Introduction
The Opentherm Monitor is a small utility that is intended to help you configure and monitor your opentherm gateway (OTGW).

## Run the image
Depending on your configuration you would start the image with something like:

```bash
docker run -d -p 8080:8080 \
  -v /src/otmonitor/otmonitor.conf:/app/otmonitor.conf
  basschipper/docker-otmonitor:latest
```

## More info
- [OpenTherm Monitor](http://otgw.tclcode.com/otmonitor.html)