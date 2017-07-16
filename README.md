# About

Dockerfiles for images to build components of project `rsyslog-enhancer`

# Image Hierarchy

```
centos6 (official centos:6)
└── centos6-minimal (tar, bzip2, which, make, git, makeself.sh)
    └── centos6-gcc (gcc-c++, libtool, autoconf, automake, byacc, flex, file, patch)
        └── centos6-rsyslog-dev (zlib-devel, libestr, json-c, zlib, libuuid, libcurl, liblogging, librdkafka)
```
