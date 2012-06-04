# Jekyll Build Pack

The Jekyll Build Pack will look for a file named `_config.yml` in the app root and
run Jekyll to create and serve the site.

This variant is designed to work on Stackato:

 http://www.activestate.com/stackato

## Usage

Specify this language pack repo in a `BUILDPACK_URL` environment
variable in a top-level `stackato.yml` file. For example: 

  name: yoursite 
  mem: 128M
  framework: buildpack
  env:
    BUILDPACK_URL: git://github.com/troytop/stackato-buildpack-jekyll.git 

Push the application to the target with `stackato push -n`. 
