# People Data Sync public information

Standalone static homepage and privacy policy for Google OAuth branding. No app API, sign-in, or database binding is attached to this Worker. The homepage links to the existing People graph.

From this directory:

```sh
npm ci
npm run build
npm run dev
npm run deploy
```

The production Google homepage URL is the deployed Worker origin; the privacy URL is that origin plus `/privacy`. Terms of service are not supplied by these pages. Google brand verification separately requires verifying domain ownership; publishing these pages is not an assertion that Google has verified the app or approved its requested scopes.

The existing graph Worker is deployed independently.
