# charts

western.social helm charts.

* `mastodon` - copied from [this mastodon fork](https://github.com/western-social/mastodon)


## Using with helm-git

You can install the `mastodon` chart with the `helm-git` plugin
like this:

```
helm repo add mastodon "git+https://github.com/western-social/charts.git@charts/mastodon?ref=v0.0.1"
```