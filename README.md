# docker-cf-bootstrap-environment
Dockerfile to create an image for CloudFoundry bootstrap.

It provides the [BOSH](https://bosh.io/docs/cli-v2/) cli tool and [BOSH bootloader
(bbl)](https://github.com/cloudfoundry/bosh-bootloader). 

The goal of this image is to provide a working Docker container for ops without mess the host system.
