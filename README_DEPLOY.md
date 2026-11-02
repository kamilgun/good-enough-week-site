# Good Enough Week — public site

Minimal static site for the Good Enough Week pre-beta public presence.

## Files

- `index.html` — public landing page
- `privacy/index.html` — privacy policy available at `/privacy/`
- `styles.css` — shared responsive styles
- `robots.txt` — basic crawler policy

## Recommended Cloudflare Pages deployment

1. Create a GitHub repository, for example `good-enough-week-site`.
2. Add these files and push to `main`.
3. In Cloudflare Dashboard, create a Pages project connected to the repository.
4. This is a plain static site:
   - Framework preset: None
   - Build command: leave empty
   - Build output directory: repository root
5. Deploy.
6. Add the custom domain `goodenoughweek.com`.
7. Optionally add `www.goodenoughweek.com` and redirect one hostname to the other.
8. Verify:
   - `https://goodenoughweek.com`
   - `https://goodenoughweek.com/privacy/`

## Before submitting the Garmin application

- Confirm both URLs load over HTTPS.
- Use `https://goodenoughweek.com` as Company Website URL.
- Use `https://goodenoughweek.com/privacy/` as Company Privacy Policy URL.
- Review the contact email in the privacy policy.
- Update the privacy policy whenever the beta architecture or data practices materially change.

## Important

This privacy policy is a practical pre-beta disclosure aligned with the currently planned product architecture. It is not a substitute for jurisdiction-specific legal advice if the product later launches commercially or at larger scale.
