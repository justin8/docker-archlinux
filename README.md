#Docker Archlinux#
[![Build Status](https://jenkins.dray.be/buildStatus/icon?job=docker_archlinux)](https://jenkins.dray.be/job/docker_archlinux)

This is an image created using a slightly modified version of the official docker script for generating an Arch Linux image. It fixes some issues encountered as well as adding my repo in for extra packages.

##Release schedule##
New versions will be posted to docker hub on the first of every month at least. Sometimes more often when major changes occur. Latest will always point at the latest release built.

##Details##
It is based off of the same script as upstream base/archlinux. However since that was never updated it does have some changes now so that it will continue to work consistently.

Based off of [mkimage-arch.sh][1]



  [1]: https://github.com/dotcloud/docker/blob/master/contrib/mkimage-arch.sh
