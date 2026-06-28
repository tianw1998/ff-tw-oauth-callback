# FF TW OAuth Callback

OAuth callback landing page for TikTok Developer API integration.

This repository serves a static HTTPS page used as the redirect URI when running OAuth flows against the TikTok Developer API for the official **Garena Free Fire TW** marketing account (@freefiretw).

The page reads the `code` and `state` query parameters from the URL and displays them so the developer can copy the code into a CLI script for token exchange.

## Live URL

https://tianw1998.github.io/ff-tw-oauth-callback/

## Used by

- TikTok app: `FF TW Marketing Analytics` (Sandbox mode)
- Purpose: weekly marketing report data automation

## Operator

Garena Free Fire TW marketing team — internal use only.
