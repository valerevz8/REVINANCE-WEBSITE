# REVINANCE Website — Development

Apple-inspired, responsive marketing landing page for REVINANCE. This implementation is maintained on the `dev` branch and is not a production deployment.

## Run locally

Open `index.html` in a modern browser. Google Fonts and the REVINANCE app icon load from external URLs, so internet access is required for those assets.

## Current experience

- Responsive desktop, tablet, and mobile layouts
- Indonesian / English language toggle
- Monthly / yearly pricing toggle
- Scroll reveal, hover transitions, hero motion, sticky navigation
- REVINANCE palette: `#252525`, `#443A35`, `#E4DDCC`, `#F8F4EE`, `#C5B49D`, with restrained gold accents
- Free and Pro pricing presentation

## Before production

- Dashboard figures are illustrative, not connected to a live account.
- Confirm pricing, feature entitlements, and legal/privacy copy.
- Marketing CTAs route to the existing app authentication and Pro plan URLs; monthly/yearly selection passes the matching `period` query parameter.
- Terms of Service and Privacy Policy link to the live app legal pages; support contact: `support@revinance.app`.
- Verify all app routes, responsive behavior, browser accessibility, and the deployed experience before production release.
- Keep production changes out of `dev` until reviewed and approved.
