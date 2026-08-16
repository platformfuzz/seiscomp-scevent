# seiscomp-scevent

![CI](https://github.com/platformfuzz/seiscomp-scevent/actions/workflows/ci.yml/badge.svg)
![Build and Release](https://github.com/platformfuzz/seiscomp-scevent/actions/workflows/build-and-release.yml/badge.svg)

Unofficial SeisComP scevent image built with public gsm. Not gempa-supported.

The process associates origins into events.

**Package:** [ghcr.io/platformfuzz/seiscomp-scevent](https://github.com/platformfuzz/seiscomp-scevent/pkgs/container/seiscomp-scevent)

## Run

```bash
docker pull ghcr.io/platformfuzz/seiscomp-scevent:latest
docker run --rm ghcr.io/platformfuzz/seiscomp-scevent:latest
```

`SCMASTER_HOST`, `SEEDLINK_HOST`, and `DB_HOST` can be overridden at run time.

## Build

```bash
docker build -t seiscomp-scevent:test .
docker run --rm seiscomp-scevent:test
```
