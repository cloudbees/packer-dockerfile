# Description

Docker image with Packer and Packer-Azure plugin installed. Packer executable is on PATH var.

# How to use this Docker image

This Docker image is intended to be used with the [Jenkins Docker Pipeline Plugin](https://wiki.jenkins-ci.org/display/JENKINS/CloudBees+Docker+Pipeline+Plugin).

Packer and Packer-Azure are installed in `/packer/bin`.

# Version 0.0.1
-   OS: Ubuntu 14.04.4 LTS
-   Common tools: curl, unzip
-   Packer: 0.9.0
-   Packer-Azure: prerelease-38bade1

# About this repository

This repository is available on [github.com/cloudbees/packer-dockerfile/](https://github.com/cloudbees/packer-dockerfile), and the automated build is on the [Docker Hub](https://hub.docker.com/r/cloudbees/packer/).

# User Feedback

## Issues

If you have any problems with or questions about this image, please submit a [GitHub issue](https://github.com/cloudbees/packer-dockerfile/issues).

## Contributing

If you have a contribution for this repository, please send a pull request.

If you want to contribute to Jenkins CI, see the [Contributing to Jenkins](https://wiki.jenkins-ci.org/display/JENKINS/contributing).

# License

The cloudbees/packer image is licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0), and this repository is too:

```
Copyright 2016 CloudBees, Inc


Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
