# Hoppy Dice Tactics website

Website created using [Hugo](https://gohugo.io/) and [Gokarna theme](https://github.com/526avijitgupta/gokarna), with [umami](https://umami.is/) for website analytics.


## Local development/testing

```
podman run --rm --publish 8080:8080 -v $(pwd):/src:Z ghcr.io/peaceiris/hugo:latest-full server --port 8080 --bind 0.0.0.0
```
