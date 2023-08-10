# Jungsoft Docker image for Metabase, based in Ubuntu, built multiarch

This docker image was created to allow using Metabase in ARM processors.

## Usage

`docker pull jungsoft/metabase`

This image was built using

`docker build --platform linux/amd64,linux/arm64 . --tag jungsoft/metabase --push`

[![Docker Image CI](https://github.com/jungsoft/metabase-arm/actions/workflows/docker-image.yml/badge.svg)](https://github.com/jungsoft/metabase-arm/actions/workflows/docker-image.yml)
