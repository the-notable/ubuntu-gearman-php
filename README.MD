## Version Info
* Ubuntu 14.04
* Gearman 1.1.12
* PHP5

## Description
This image is just a base Ubuntu 14.04 image with Gearman 1.1.12 (compiled and installed) and PHP5.

This image is meant to be used as a base image for other builds. The Gearman package contains the gearman daemon library
(gearmand) and also the gearman client library. Using this image as a base you can build a gearman worker server, or
use it as a base for an application server that needs to use the gearman client.

Because this image is meant to be used as a base image and as such contains no entry points and doesn't expose any ports.