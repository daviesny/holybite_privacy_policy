# HolyBite public policy website

Contains public policy documents only. Keep the Flutter source in its existing private repository.

## Publish
1. Create a separate public repository named `holybite_privacy_policy` under `daviesny`.
2. Upload `index.html`, `terms.html`, and `.nojekyll` to the repository root.
3. Open Settings → Pages. Select Deploy from a branch → main → / (root), then Save.
4. Wait for deployment and verify both pages open without signing in.

Expected URLs (not verified live yet):
- Privacy: https://daviesny.github.io/holybite_privacy_policy/
- Terms: https://daviesny.github.io/holybite_privacy_policy/terms.html
- Account deletion: https://daviesny.github.io/holybite_privacy_policy/#account-deletion

## Before publishing
- Confirm Apkerooo is the correct provider name and apkerooo@gmail.com is a monitored support address.
- Publish the updated Firestore rules and distribute the updated app using communityFasting markers.
- Confirm the under-13 statement matches your intended audience and Play Console declarations.
- Check current advertising consent and data-safety declarations against the actual app configuration.
- Review provider retention practices. The documents deliberately do not promise a made-up fixed retention period.

GitHub Pages links become usable after deployment. Updating these files does not automatically update Play Console or the app.
