# Improve website security and performance with .htaccess rules

Here helpful .htaccess rules which help to improve website security, performance and SEO are collected.

## Improve website security
* Add security headers X-Frame-Options
* Add a HSTS and PKP header on HTTPS websites. If you need help, use the [HPKP Hash Generator](https://report-uri.io/home/pkp_hash)
* Add a CSP header. If you need help, use the [CSP Builder](https://report-uri.io/home/generate).
* Hide Apache and PHP version.

You can test your results at [securityheaders.io](https://securityheaders.io/).

## Improve performance
* Add expires headers.
* Enable gzip compression.

## Improve SEO
* Add a 301 redirection from www.mydomain.org to mydomain.org.
* Provide custom error documents.

Please note that applying this .htaccess unchanged may cause errors with your Apache configuration. Rules which need customization are commented out.