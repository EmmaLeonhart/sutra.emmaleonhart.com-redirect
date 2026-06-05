# sutra.emmaleonhart.com redirect

Static GitHub Pages site that redirects **sutra.emmaleonhart.com** → <https://sutra.yantraos.org/>.

Sutra is now part of the Yantra ecosystem, so it lives at the subdomain
`sutra.yantraos.org` (under the Yantra domain `yantraos.org`). The legacy
subdomain `sutra.emmaleonhart.com` forwards all traffic here (preserving path,
query string, and hash). GitHub Pages issues a free Let's Encrypt certificate for
the custom domain so `https://sutra.emmaleonhart.com` keeps a valid TLS certificate.

## DNS setup (to do at the registrar)
Point `sutra.emmaleonhart.com` at GitHub Pages with a CNAME record:
- `sutra.emmaleonhart.com` → `emmaleonhart.github.io` (or the appropriate Pages host)

The `CNAME` file in this repo sets the Pages custom domain to `sutra.emmaleonhart.com`.
