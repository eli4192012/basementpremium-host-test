# Basement Premium — GitHub Pages hosting test

This is a separate public hosting trial of the existing Basement app, retaining its games, media catalog, proxy links, local file previews, mandatory terms, and browser-local staff access.

Shared alerts are not connected here: GitHub Pages serves static files and does not run the existing alert backend. The interface explicitly labels that limitation. No request is made to an unsupported alert endpoint.

The hosted copy checks its own `version.json` once per minute while entered, visible, and online, daily from 8:30 a.m. through the 3:20 p.m. minute in the device's local time. A newer published release offers a refresh button. Opening or manually refreshing loads the published app, subject to GitHub's deployment and caching delays. This is not automatic synchronization from the Cloudflare site.

The download page creates a shortcut to this repository's Pages address. Browser storage is separate from the original website. External links and this site can still be blocked by a school filter; access on a school device must be tested there.

Only public frontend assets are published. The existing Cloudflare app and its backend are unchanged.
