# ScribeKeep Website

Your words. Your notes. Your cloud.

This repository contains the public GitHub Pages website for the ScribeKeep iOS app, including:

- Product information
- Privacy Policy
- Support information

Public site: https://scribekeep.github.io/

The ScribeKeep iOS application itself lives in a separate, private repository. **Do not** put any iOS source code, OAuth credentials, private keys, certificates, or other sensitive application configuration in this repository.

## Structure

```
index.html                    Homepage
privacy/index.html            Privacy Policy (App Store privacy policy URL)
support/index.html            Support page (App Store support URL)
assets/style.css              Shared stylesheet
assets/scribekeep-icon-1024.png  Approved master app icon (source)
assets/scribekeep-icon.png       Web-sized icon (header + homepage)
assets/favicon-32x32.png         Favicon
assets/favicon-16x16.png         Favicon
assets/apple-touch-icon.png      Apple touch icon
```

The site is fully static — plain HTML and CSS, no JavaScript frameworks, build tools, or package managers. GitHub Pages serves it directly from the root of the `main` branch.

## Previewing locally

From the repository root, start a simple static HTTP server:

```
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Icon assets

Brand asset: `assets/scribekeep-icon-1024.png` is the approved ScribeKeep master app icon (unmodified). `assets/scribekeep-icon.png`, `assets/favicon-32x32.png`, `assets/favicon-16x16.png`, and `assets/apple-touch-icon.png` are direct resizes of that master, used for the header mark, homepage hero, favicon, and Apple touch icon respectively.
