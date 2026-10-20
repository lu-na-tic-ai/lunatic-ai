# Lunatic AI

A single-page, English-language coming-soon site for Lunatic AI's planned AI-assisted image and video editing tools.

## Run locally

Open `index.html` in a browser. No package installation or build step is required.

## Publish with GitHub Pages

This static site can be published directly from the `main` branch without a build workflow.

1. In **Settings > Pages**, choose **Deploy from a branch**, then select `main` and `/ (root)`, and save.
2. Add `www.lunatic.ai` as the custom domain. Keep the root `CNAME` file in the repository.
3. Configure DNS at the domain provider with these records:

| Type | Name | Value |
| --- | --- | --- |
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |
| CNAME | `www` | `lu-na-tic-ai.github.io` |

Add the custom domain in GitHub Pages before changing DNS. DNS changes may take up to 24 hours to propagate. Once GitHub verifies the domain, enable **Enforce HTTPS** in Pages settings.

## Before publishing

- The interest form sends a prepared email to `info@lunatic.ai` by opening the visitor's email application. It does not store submissions.
- The hero portrait is stored locally in the project. The web fonts load from Google Fonts and require an internet connection.
- Add legal/privacy pages and consent handling as appropriate before collecting or processing personal data.
