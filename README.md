Cacher is a image that contains various caching items

[![DOI](https://zenodo.org/badge/291716314.svg)](https://doi.org/10.5281/zenodo.4553191)

squid - caches web downloads - also picks the fastest mageia RPMS
distcc/ccache - caches compiles
git-cache-httpd-server - caches git downloads
verdaccio - caches npm

To run the cacher:
Edit proxy.sh with location of cacher

docker-compose up  or podman-compose up
source proxy.sh
