# sanamhera.com

Live site: [www.sanamhera.com](https://www.sanamhera.com)

GitHub Pages source for the personal site. Custom domain is set via the `CNAME` file.

## GoDaddy DNS

In GoDaddy → domain `sanamhera.com` → DNS, remove parking / coming-soon records, then add:

| Type | Name | Value |
|---|---|---|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `sanamhera.github.io` |

Then in this repo: **Settings → Pages → Custom domain** → `www.sanamhera.com` → Save, and tick **Enforce HTTPS** once DNS is green.
