# Analytics Lab — Experimental Website

This is a small static website for a university Google Analytics 4 practical.

## Setup
1. Publish this repository with GitHub Pages.
2. In Google Analytics, create a GA4 property and Web data stream for the published GitHub Pages URL.
3. Copy the Measurement ID (format: `G-XXXXXXXXXX`).
4. In `index.html`, replace both occurrences of `G-XXXXXXXXXX` with your actual Measurement ID.
5. Remove the HTML comment markers around the GA4 script block (the `<!--` before the script and the `-->` after it).
6. Commit the change and wait for GitHub Pages to redeploy.
7. Visit the public site and check Reports → Realtime in Google Analytics.

Do not publish the placeholder ID. Use your own Measurement ID.
