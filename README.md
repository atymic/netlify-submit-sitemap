# Submitting sitemaps on deploy with Netlify

There's plenty of static site generators out there, and most support generating sitemaps. To make sure google indexes
your pages as quickly as possible, it's a good idea to ping them with your sitemap when it's updated.

Netlify provides some hooks which can be used to run functions once the deploy is complete. This allows us to just ping
google when production is deployed.

[You can read the tutorial here](https://atymic.dev/tips/netlify-submit-sitemaps/).
