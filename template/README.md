# Privacy-policy template

Reusable CNTRL Design privacy policy. Use it to stand up a new app's policy page fast.

## To create a new app's policy

1. **Copy** `template/privacy/` → `<appname>/privacy/`
   (so it serves at `https://cntrldesign.com/<appname>/privacy`).
2. **Find & replace** in the new `index.html`:
   - `{{APP_NAME}}` → the app's name (e.g. `FIFO`)
   - `{{APP_TAGLINE}}` → the App Store subtitle
   - `{{LAST_UPDATED}}` → today's date (e.g. `26 June 2026`)
   - `{{SHORT_VERSION_WHAT_LEAVES}}` → one sentence on what leaves the device
   - `{{DESCRIBE_WHAT_LEAVES_THE_DEVICE_AND_WHY}}` → section 02 detail
   - `{{LIST_THIRD_PARTIES}}` → the third parties this app uses
3. **Rewrite section 02** ("Information that leaves your device") so it matches what
   *that* app actually sends off-device. Accuracy matters — App Review compares the
   policy to the app's real behaviour. Delete any part that doesn't apply.
4. **Link it** from the app (the paywall / settings privacy link) and paste the URL
   into App Store Connect → App Privacy → Privacy Policy URL.

The shared look (`/style.css`, `/img/logo-*.png`, `/favicon.png`) is inherited automatically —
don't duplicate it. `FIFO` (`/fifo/privacy/`) is the worked example to copy from.
