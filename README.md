# site: citylore.app

The public website, served by GitHub Pages from the public repo
[birdsongapps/citylore-site](https://github.com/birdsongapps/citylore-site) at https://citylore.app.

- `index.html`: the landing page (no cookies, nothing loaded from other sites).
- `oauth/client-metadata.json` is added at publish time from `apps/mobile/oauth/client-metadata.json`
  (generated from `apps/mobile/src/auth/oauthConfig.ts`). Its URL is the phone app's OAuth client ID,
  so it must always match the app.

Publish after changing either: `site/publish.sh` (pushes to the public repo; Pages updates in a minute).
