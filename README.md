# SSL Checker

The project check SSL expiration via a single PHP file.

The script loads the domain from whatever GET parameters, fetches SSL informaion of each domain, sorts by expiration time, and displays to the output.

The project deploy on Heroku and use Cloudflare Workers for reverse proxy.

Check the demo here: [https://ssl-checker.spicydog.org/?domain=spicydog.org](https://ssl-checker.spicydog.org/?domain=spicydog.org).
