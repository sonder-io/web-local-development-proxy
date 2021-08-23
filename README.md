# README

this is a simple proxy which helps sonder portal developers to develop local code easily.

- We already set domain in route53  `local.staging.sondersafe.com` -> 127.0.0.1. So when accessing "local.staging.sondersafe.com" it will just access this proxy.
- The proxy is using caddy, with configuraiton as Caddyfile. The configuraion would be straightforward: follow the prefix, and configure the different parts of puzzle. Read and make your change there.
- Start the server by running `docker-compose up` and then access http://local.staging.sondersafe.com from browser.