# heroku-buildpack-git-submodules

A very simple buildpack to convince Heroku to update your submodules during a deploy.

Heroku will normally (do this automatically)[https://devcenter.heroku.com/articles/git-submodules].

However, if you're using Heroku's Dashboard UI to deploy or using review apps, it will not.

In these cases you require a buildpack like this one.

## Installation

> heroku buildpacks:add https://github.com/dmathieu/heroku-buildpack-submodules

## Inspiration and Credit

+ https://github.com/dmathieu/heroku-buildpack-submodules
+ https://github.com/mietek/heroku-buildpack-submodule-example
