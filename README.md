# airaadaptive.com

Official website of AIRA Adaptive. Static HTML served by GitHub Pages at https://airaadaptive.com.

- No build step, no JavaScript, no third-party scripts or trackers.
- Shared styles: `assets/site.css` (light and dark themes via CSS variables).
- `CNAME` sets the custom domain. Do not delete it.
- The MCP server (`https://mcp.drbukret.com/functions/v1/aira-adaptive`) and the OAuth sign-in page are hosted elsewhere and are not part of this repository.

## Adding a page

1. Create `<section>/index.html` (for example `integrations/`, `science/`, `pricing/`) by copying `docs/index.html`.
2. Keep the same `<header>` and `<footer>`, and change `<title>`, `<meta name="description">` and `<main>`.
3. Use relative links (`../assets/site.css` one level deep).
4. Add the URL to `sitemap.xml`.
5. Before claiming anything clinical, regulatory or commercial, get it approved by the owner.

## Legal pages

Privacy and Terms currently link to the published texts on the AIRA Cloud project. New versions (with the Claude section) will be added as `privacy/` and `terms/` after owner approval.
