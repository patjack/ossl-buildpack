# OpenSSL buildpack

This builds a Heroku instance with the default Heroku buildpack linked to OpenSSL 1.0.1e.

## Use with ddollar/heroku-buildpack-multi
 
    $ heroku config:set BUILDPACK_URL=https://github.com/ddollar/heroku-buildpack-multi

    $ cat .buildpacks
    https://github.com/heroku/heroku-buildpack-python
    https://github.com/gtank/ossl-buildpack.git


The binaries referenced in bin/compile were produced with Heroku anvil from the
standard sources. If you do use this, please consider hosting your own copies.
