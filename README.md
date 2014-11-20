# buildpack-deps for Ubuntu [![](https://quay.io/repository/wantedly/buildpack-deps/status)](https://quay.io/repository/wantedly/buildpack-deps)
This Dockerfile is ported from debian's buildpack-deps to Ubuntu.
For more information about this, please see [original buildpack-deps README](https://github.com/docker-library/buildpack-deps).

![](https://raw.githubusercontent.com/docker-library/docs/master/buildpack-deps/logo.png)

## HOW TO USE
This stack is designed to be the foundation of a language-stack image for ubuntu.

```
FROM quay.io/wantedly/buildpack-deps:14.04
MAINTAINER someone <someone@example.com>
...
```

## SUPPORTED TAGS

* [`12.04`](12.04/Dockerfile)
* [`14.04`](14.04/Dockerfile)

## LICENSE
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)
