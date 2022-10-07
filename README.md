# znk.io static hosting

This repository provides a ready-to-fork example to start hosting a static website under the domain znk.io.

## Features

- Instant activation
- SSL certificate
- Wildcard name resolution
- Advanced features with [Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)
- Deploy your build workflow using GitHub actions
- Manage content with Git under the hood

## Use cases

- Documentation
- POCs
- temporary websites
- SSG showcases
- pretty much any static content


## How-to

- Check the subdomain availability : mybeautifulsite.znk.io
- Fork this repository or create a new one under the Zenika GitHub organization
- Name it using the pattern : Zenika/mybeautifulsite.znk.io
- update the CNAME file with your subdomain
- In Settings / Pages, fill the subdomain mybeautifulsite.znk.io
- Wait for the message "DNS check successful"
- Check "Enforce HTTPS"
- Et voilà !

## Rules

- Do not host or use subdomains that you would not use in a professional context
- Do not use personal data
- Do not enable robots crawling (for the moment)
- Using a backend REST APIs is not tested/supported

Have fun !
