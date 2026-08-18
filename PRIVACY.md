# Search Button privacy policy

_Last updated: 18 August 2026_

**Search Button collects no data.**

The extension has a single purpose: restoring the Google Search submit button on the Google homepage
when the page is served without one. It runs only there, and only to put that button back.

## What it does not do

- It makes **no network requests**. Nothing is sent anywhere, so no data can leave your device.
- It **stores nothing**, on the device or elsewhere. It requests no storage permission and uses no
  browser storage.
- It contains **no analytics, no tracking, no accounts and no remote code**. Every line ships inside
  the package.
- It requests **no browser permissions** beyond running on the Google homepage, which is the page it
  modifies. Its manifest has no `permissions`, `optional_permissions` or `host_permissions` entry.

## What it reads

While it runs on the Google homepage it reads three things from that page, none of which leaves it:

1. whether the page's search form is present,
2. whether the row of buttons under the search box already holds Google's own search button,
3. the page's language attribute, so the restored button carries the label Google itself uses for
   that language.

This is reading the page the extension is displayed in. It is not collection: nothing is recorded,
stored, profiled or transmitted.

## Data sharing

There is none. No data is collected, so none is sold, transferred to third parties, used for purposes
unrelated to the extension's single purpose, or used to determine creditworthiness or for lending.

## Contact

- Email: help@c0nn3ct.info
- Issues: https://github.com/c0nn3ct-info/search/issues
