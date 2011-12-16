# Jekyll Build Pack

The Jekyll Build Pack will look for a file named `_config.yml` in the app root and
run Jekyll to create and serve the site.

## Usage

Add this language pack to your `BUILDPACK_URL`.

    heroku config:add BUILDPACK_URL="http://github.com/markpundsack/heroku-buildpack-jekyll.git"
    
Or, with a recent version of the heroku gem, set it at creation time:

    heroku create --stack cedar --buildpack http://github.com/markpundsack/heroku-buildpack-jekyll.git
