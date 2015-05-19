dokku-bower-grunt-build
=================

This plugin will install Bower and pull in dependencies. It will then
install grunt-cli and run the 'build' task. Any Grunt specific node
modules other than grunt-cli should be specified in Gruntfile.js.

## Install

On your dokku server run:
```sh
> git clone https://github.com/samzhao/dokku-bower-grunt-build /var/lib/dokku/plugins/bower-grunt-build
> dokku plugins-install
```
