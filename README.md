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
index.html          Homepage
privacy/index.html  Privacy Policy (App Store privacy policy URL)
support/index.html  Support page (App Store support URL)
assets/style.css     Shared stylesheet
```

The site is fully static — plain HTML and CSS, no JavaScript frameworks, build tools, or package managers. GitHub Pages serves it directly from the root of the `main` branch.

## Previewing locally

From the repository root, start a simple static HTTP server:

```
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Icon assets

No approved ScribeKeep app icon currently exists in this repository. The header currently uses a simple text mark ("SK") in place of an icon image. Once an approved icon is available, it can be added under `assets/` and referenced from the header and as a favicon without further layout changes.
