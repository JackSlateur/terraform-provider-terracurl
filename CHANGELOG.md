## 2.4.0

FEATURES:

- Add `terracurl_request` action support for on-demand HTTP requests via `terraform apply -invoke` (Terraform 1.14+). Based on #127 by @jen20.

## 2.3.1

BUG FIXES:

- Fix Host header override when `Host` is set in request header maps (fixes #79). Based on #97 by @JoshBlades.

## 2.3.0

FEATURES:

- Add HTTP and HTTPS proxy support via environment variables and provider attributes (`http_proxy`, `https_proxy`, `no_proxy`)
- Proxy support applies to TLS/mTLS requests as well as plain HTTP requests
- Add HTTP Proxy Support guide, examples, and tests

## 2.2.0 

FEATURES:

- Bug fixes with state upgrade
- Documentation updates
