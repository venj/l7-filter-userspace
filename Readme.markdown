#l7-filter-userspace

## What is this?

This source code is basically the original l7-filter-userspace src package with a teeny-tiny patch made the original source code build on ubuntu 14.04.

## How-to
1. Install build tools
    
    ```
    apt-get install -y vim build-essential fakeroot devscripts debhelper quilt dh-make
    apt-get install -y autotools-dev libnetfilter-conntrack-dev libnetfilter-queue-dev
    ```

2. Clone the project
3. cd l7-filter-userspace_0.12-beta1
4. debbuild -us -uc

That it. 

------

- l7-filter-userspace: [Visit](http://l7-filter.sourceforge.net/HOWTO-userspace)
- l7-filter-userspace package on launchpad: [Visit](https://launchpad.net/ubuntu/+source/l7-filter-userspace)
