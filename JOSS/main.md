---
title: 'qemu-user-static (qus) and docker'
tags:
  - docker
  - software development
  - software deployment
  - sandbox
  - reproducibility
  - reproducible research
  - prototyping
authors:
  - name: Unai Martinez-Corral
    orcid:
    affiliation: "1"
affiliations:
  - name: No affiliations.
    index: 1
date:
bibliography:
---

# Summary

This repository contains utilities, examples and references to build and execute OCI images (aka [docker](https://www.docker.com/) images) for foreign architectures using [QEMU](https://www.qemu.org/)'s user-mode emulation. Multiple minimal working and non-working setups to build and execute `arm64v8` containers on `amd64` are configured and tested on [Travis CI](https://travis-ci.com/), so that the full flow is public. Moreover, docker images are provided for each of seven host architectures officially supported by Docker, Inc. or built by official images ([docker-library/official-images: Architectures other than amd64?](https://github.com/docker-library/official-images#architectures-other-than-amd64)): `amd64`, `i386`, `arm64v8`, `arm32v7`, `arm32v6`, `s390x` and `ppc64le`.
