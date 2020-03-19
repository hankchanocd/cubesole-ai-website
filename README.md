# cubesole.ai

Official website for cubesole.ai.

The website shows the ongoing AI research that powers Cubesole's infrastucture.

## Changelog

**2019-Jul-23:** `v1` published.

**2020-Mar-15:** Form submission enabled with AWS Lambda. `sendmail.cubesole.ai/send` handles the submission and emailing.

**2020-Mar-16:** `www` is redirected to the naked domain, so to limit the scope of `access-control-allow-origin` from `sendmail.cubesole.ai/send` to just `https://cubesole.ai`.

**2020-Mar-17:** Use API Gateway to strengthen the CDN with added security headers.
