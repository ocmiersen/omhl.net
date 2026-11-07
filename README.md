# omhl.net

Source for [omhl.net](https://omhl.net), a write-up of my home lab: an interactive photo of the rack, the network layout, and the services I run.

It's a static site with no build step. `public/index.html` holds the page, styles and script, and `public/rack.webp` is the rack photo. It's served by Cloudflare Workers (static assets, configured in `wrangler.jsonc`) and deploys on every push to `main`.

Icons: brand marks from [Simple Icons](https://simpleicons.org) (CC0 1.0), [Font Awesome](https://fontawesome.com) (CC BY 4.0) and generic icons from [Material Design Icons](https://pictogrammers.com/library/mdi/) (Apache 2.0).
