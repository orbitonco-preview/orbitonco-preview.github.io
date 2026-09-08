# Orbit Veterinary Oncology — preview build

This repository holds **only the compiled output** of a site under review.
It is not the source, and it is not the live site.

- Live site: https://orbitonco.com/
- This copy is served for review only, and is blocked from search indexing
  by `robots.txt` and a `noindex` meta on every page.

Two things behave differently here than they will in production:

- **The contact form does not send.** No Web3Forms key is configured yet, so
  the form tells the visitor it is not connected and offers the email address
  instead. That is the intended fallback, not a bug.
- **No security headers.** Those come from `.htaccess` on the Apache host and
  do not apply on GitHub Pages.
