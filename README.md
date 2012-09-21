# puppetmaster-bootstrap

Bootstrap Puppetmaster on Ubuntu with Stored Configuration and PostgreSQL.

Only tested on Ubuntu 12.04 LTS.

## How to use

Run as root

    curl -o puppetmaster-bootstrap -s https://github.com/pkhamre/puppetmaster-bootstrap/raw/master/puppetmaster-bootstrap
    chmod +x puppetmaster-bootstrap
    ./puppetmaster-bootstrap

## Todo

* Bootstrap a git(olite?) environment for modules
* Set up nginx + unicorn
