# realzjc.github.io

This site has moved. It now redirects to my current personal site at
[jczhao1.github.io](https://jczhao1.github.io/).

I keep this repo only so the old link I gave out (https://realzjc.github.io) still
works without anyone having to update it. `index.html` is a single redirect page:
it uses a client-side `window.location.replace`, with a `<meta http-equiv="refresh">`
and a `rel="canonical"` tag as fallbacks for crawlers and script-blocking browsers.

## If the destination ever changes

Edit the URL in `index.html` in three places (the `canonical` link, the `meta refresh`,
and the `window.location.replace` call), then push to `main`.

## Deploy

GitHub Pages is set to serve the `main` branch, root folder. Push and wait a minute or two.
No build step.
