# Travary support site

The public support, privacy and terms pages for the Travary app, served by
GitHub Pages at https://matk44.github.io/travary_support/.

| Page | File | Use it for |
|---|---|---|
| Support | `index.html` | App Store "Support URL", Google Play "Website" |
| Privacy Policy | `privacy.html` | App Store and Google Play privacy policy URL, the in-app paywall |
| Terms of Use | `terms.html` | The in-app paywall (Apple requires a Terms/EULA link for subscriptions) |
| Delete your data | `delete-account.html` | Google Play's "Delete account URL" (Data safety) |

Plain HTML and one stylesheet (`assets/style.css`), no build step. Edit a
page, commit and push to `main`; GitHub Pages republishes in a minute or two.

Keep the privacy policy in step with the app: when the app starts collecting
something new (analytics, a new provider), update `privacy.html` and its
"Effective" date before releasing that version.

Contact: dreamprayer.dev@gmail.com
