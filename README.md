# consent — Google Tag Manager Consent Mode

Applies [Google Consent Mode](https://developers.google.com/tag-platform/security/concepts/consent-mode) from a visitor’s choice on the [consent](https://consent.cosmoops.com) cookie banner.

Use this when you want Tag Manager to send Consent Mode signals. You still need the consent embed script on the page for the banner itself.

## Setup

1. Import this template into your GTM container (**Templates → Tag Templates → New → Import**), or install it from the [Community Template Gallery](https://tagmanager.google.com/gallery) once published.
2. Create a tag from the template.
3. Set the trigger to **Consent Initialization – All Pages** so it runs before other tags.
4. (Optional) Add region-specific default consent rows if you need different defaults by region. Otherwise the Global fallback denies all except necessary.
5. Publish the container.
