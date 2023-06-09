# Hoppy Dice Tactics website

Website created using [Hugo](https://gohugo.io/) and [Gokarna theme](https://github.com/526avijitgupta/gokarna), with [Un-static](https://un-static.com/) for forms and [umami](https://umami.is/) for website analytics.


## Local development/testing

```
podman run --rm --publish 8080:8080 -v $(pwd):/src:Z docker.io/klakegg/hugo:ext-ubuntu server -p 8080
```
