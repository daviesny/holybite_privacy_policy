# HolyBite public policy website

Contains HolyBite's public policy pages and the buddy-invite landing page. Keep the Flutter source in its existing private repository.

## Publish
The public repository `daviesny/holybite_privacy_policy` already hosts the privacy and terms pages. Add `buddy-invite.html` to that repository's root on `main`; GitHub Pages is already enabled for the site. After it deploys, verify the invite page opens without signing in.

Expected URLs (not verified live yet):
- Privacy: https://daviesny.github.io/holybite_privacy_policy/
- Terms: https://daviesny.github.io/holybite_privacy_policy/terms.html
- Account deletion: https://daviesny.github.io/holybite_privacy_policy/#account-deletion
- Buddy invite: https://daviesny.github.io/holybite_privacy_policy/buddy-invite.html?code=INVITE_CODE

## Before publishing
- Confirm Apkerooo is the correct provider name and apkerooo@gmail.com is a monitored support address.
- Publish the updated Firestore rules and distribute the updated app using communityFasting markers.
- Confirm the under-13 statement matches your intended audience and Play Console declarations.
- Check current advertising consent and data-safety declarations against the actual app configuration.
- Review provider retention practices. The documents deliberately do not promise a made-up fixed retention period.

GitHub Pages links become usable after deployment. The buddy invite page opens the installed app when the user taps its button, and shows a copyable code as a fallback. Updating these files does not automatically update Play Console or the app.
