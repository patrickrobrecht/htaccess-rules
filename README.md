# Improve website security and performance with .htaccess rules

Here helpful .htaccess rules which help to improve website security, performance and SEO are collected.

* Found an error? Having ideas to improve this recommendation? Please report [the issue](https://github.com/patrickrobrecht/htaccess-rules/issues).
* Want to provide an extension? Create a [pull request](https://github.com/patrickrobrecht/htaccess-rules/pulls).

## Improve website security
* Add a SSL certificate. You can get free SSL certificates with [Let's Encrypt](https://letsencrypt.org/) or [SSL For Free](https://www.sslforfree.com/).
* If HTTPS is supported, redirect HTTP to HTTPS requests.
* Add security headers X-Frame-Options
* If HTTPS is supported, add a HSTS and PKP header. If you need help, use the [HPKP Hash Generator](https://report-uri.io/home/pkp_hash).
* Add a CSP header. If you need help, use the [CSP Builder](https://report-uri.io/home/generate).
* Hide Apache signature and PHP version sometimes placed in HTTP responses and on error pages.
* Disallow access to private files.

You can test your results for HTTP header security at [securityheaders.io](https://securityheaders.io/).

## Improve performance
* Add expires headers.
* Enable gzip compression.

## Improve SEO
* Add a 301 redirection from www.mydomain.org to mydomain.org.
* Provide custom error documents.

Please note that applying this .htaccess unchanged may cause errors with your Apache configuration. Rules which need customization are commented out.