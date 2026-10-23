# OrgHop

OrgHop: Quick search for Salesforce is a Chrome extension that jumps to any Salesforce Setup page, app, object or record in one click.

- **Install:** [Chrome Web Store](https://chromewebstore.google.com/detail/orghop-quick-search-for-s/fjilbkaffbfbplfmpjacgmadcchpmfbi)
- **Website and guides:** [bizstow.github.io/orghop](https://bizstow.github.io/orghop/)
- **Report a bug:** [open a bug report](https://github.com/bizstow/orghop/issues/new?template=bug_report.yml). Issues are public, so please leave out usernames, record names, org URLs and screenshots with customer data.
- **Release notes:** [Releases](https://github.com/bizstow/orghop/releases)
- **Privacy policy:** [bizstow.github.io/orghop/privacy.html](https://bizstow.github.io/orghop/privacy.html)

This repository holds OrgHop's public website, guides and issue tracker. The extension's source code is not published here.

## The website

GitHub Pages serves the site from the root of `main`. Every page is plain HTML and CSS.

- `index.html` is the home page. Its "Add to Chrome" buttons, like the ones in every page's header, link to the Chrome Web Store listing.
- `privacy.html` is the privacy policy. Its address is in the Chrome Web Store listing, so don't rename or move it.
- `assets/css/site.css` styles every page. Its colors follow the extension's popup and icon. `assets/img/` holds the icon and screenshots, cropped from the extension's `store-assets/`.
- How-to guides go in `guides/`, one plain HTML page per guide. Copy an existing guide as a starting point, then add a card for it to `guides/index.html` (and to the Guides section of `index.html` if it's one of the most useful). The site has no build step, so every page also works when opened straight from disk.

OrgHop is an independent project and is not affiliated with or endorsed by Salesforce, Inc.

© 2026 MA Husain, trading as Bizstow. All rights reserved.
