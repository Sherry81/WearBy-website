# WearBy Website

A lightweight static showcase site for WearBy. No build step, package install,
or server-side runtime is required.

## Pages

- `index.html` — home and app overview
- `about.html` — what WearBy is and how it works
- `privacy-policy.html` — public privacy policy
- `terms-and-conditions.html` — terms for marketplace members

## Preview locally

Open `index.html` in a browser, or serve this folder with any static file
server. Keep the `assets` folder next to the HTML files.

## Publish

Upload the website files and `assets` folder to an HTTPS static host. Point
`www.wearby.com.pk` at that host and configure the privacy-policy URL in the
app to the published `privacy-policy.html` address.

Before publication, review the privacy policy and terms against the actual
service, data practices, contact process, and applicable legal requirements.
The separate `delete-account.html` file is not included in the showcase package;
configure it with the project's public Supabase URL and publishable key before
hosting it as the account-deletion route.

## Brand files

The website uses the WearBy logo, favicon, and local Nunito font files in
`assets`. Colors and responsive layout are in `styles.css`; the small mobile
navigation behavior is in `site.js`.
