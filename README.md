# Jekyll Buildpack

The Jekyll Buildpack will look for a file named `_config.yml` in the app root and
run Jekyll to create and serve the site.

## Usage

Example usage:

```bash
λ ls
_config.yml  css  index.html  _layouts  _posts
λ heroku create --buildpack git://github.com/bacongobbler/heroku-buildpack-jekyll.git
Git remote heroku added
λ git push heroku master

-----> Fetching custom git buildpack... done
-----> Jekyll app detected
-----> Setting environment variables
-----> Installing jekyll
Successfully installed jekyll-1.4.0
21 gems installed
-----> Compiling Jekyll site
    Generating... done.
-----> Discovering process types
    Procfile declares types  -> (none)
    Default types for Jekyll -> web
-----> Compiled slug size: 9.2MB
-----> Launching... done, v4
```
