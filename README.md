# Privacy policy - Shrink Image&Video

This repository exists for one reason: to serve the privacy policy for the
Android app **Shrink Image&Video** (`com.sunsinedimon.imageoptimayzer`) from a
public HTTPS URL, as required by the Google Play Developer Program Policy.

**Do not edit `index.html` here.** It is a generated copy of
`store/privacy-policy.html` from the private application repository, written by
`tools/publish_privacy_policy.ps1`. Any edit made here is overwritten on the
next publish and will drift from what the app's Settings screen links to.

## Contents

- `index.html` - the policy, effective 30 September 2026
- `.nojekyll` - serve the folder verbatim, without Jekyll processing

The page is fully self-contained: no scripts, no external resources, no cookies,
no visitor analytics.

## Enabling GitHub Pages

Repository **Settings > Pages > Build and deployment > Source: Deploy from a
branch**, then pick the default branch and the `/ (root)` folder.

The page is named `index.html` rather than `privacy-policy.html` because
GitHub Pages resolves a directory URL to `index.html` and nothing else. It is
live at `https://sunshinedimon.github.io/shrink-image-video-privacy/` - that
exact URL also goes in:

1. Google Play Console > Policy > App content > Privacy policy
2. `util/ExternalLinks.PRIVACY_POLICY_URL` in the application source

## Why a separate public repository

GitHub Pages can only build from a private repository on a paid plan, but a
Pages *site* is public even when the repository behind it is private. A tiny
public repository containing nothing but this policy needs no paid plan and
exposes no application code.