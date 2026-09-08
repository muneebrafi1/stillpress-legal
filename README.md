# stillpress-legal

Stillpress legal and support pages — privacy policy, terms of use, open-source
licenses, account deletion and support. Served by GitHub Pages from `main`.

| Page | URL |
|---|---|
| Support | https://muneebrafi1.github.io/stillpress-legal/ |
| Privacy Policy | https://muneebrafi1.github.io/stillpress-legal/privacy.html |
| Terms of Use | https://muneebrafi1.github.io/stillpress-legal/terms.html |
| Licenses | https://muneebrafi1.github.io/stillpress-legal/licenses.html |
| Delete your account | https://muneebrafi1.github.io/stillpress-legal/delete-account.html |

Every claim on these pages is checked against the app's code before it is
written (see `src/lib/legal.ts` and `app/legal/[page].tsx` in the app repo);
when the app starts doing something new with data, change the page first and
bump the date at the top.

To move to a custom domain: add a `CNAME` file containing the domain, point
the domain's DNS at GitHub Pages (four `A` records for the apex, or a `CNAME`
record for `www`), and update the URLs in `src/lib/legal.ts`.
