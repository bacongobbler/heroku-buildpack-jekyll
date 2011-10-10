# Jekyll Build Pack

The Jekyll Build Pack will look for a file named `_config.yml` in the app root and
run Jekyll to create and serve the site.

## Usage

Add this language pack to your `BUILDPACK_URL`.

    heroku config:add BUILDPACK_URL="http://github.com/markpundsack/heroku-buildpack-jekyll.git"
