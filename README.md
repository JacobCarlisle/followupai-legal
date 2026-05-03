# FollowUp AI Legal & Support Site

This is a static GitHub Pages site for the FollowUp AI App Store submission.

## Files

- `index.html` — legal and support landing page
- `privacy.html` — Privacy Policy URL for App Store Connect
- `privacy-choices.html` — optional User Privacy Choices URL
- `terms.html` — Terms of Use
- `support.html` — Support URL for App Store Connect
- `styles.css` — shared styling
- `.nojekyll` — tells GitHub Pages to serve static files directly
- `app-store-metadata.md` — App Store Connect URL fields and checklist

## Required edits before publishing

1. Replace every instance of `YOUR_SUPPORT_EMAIL@example.com` with a working support email.
2. Confirm the final public app name is exactly `FollowUp AI`. If the App Store name differs, update the page titles and body copy.
3. Replace or add the legal owner name in the footer and legal documents if needed.
4. Review the Privacy Policy against the app’s actual behavior:
   - AI model provider
   - analytics/crash reporting SDKs
   - authentication provider
   - cloud database/storage
   - device permissions, such as notifications, contacts, calendars, microphone, or files
   - third-party integrations
   - in-app purchases/subscriptions
   - whether user content is stored, encrypted, synced, exported, or deleted
5. Update App Store Connect privacy disclosures so they match the app and the published Privacy Policy.

## How to publish with GitHub Pages

1. Upload these files to the root of the `JacobCarlisle/followupai-legal` repository.
2. Commit the files to the `main` branch.
3. Go to repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/root`, then save.
6. After GitHub finishes publishing, verify the URLs below in a private/incognito browser.

## Expected public URLs

```text
Home:
https://jacobcarlisle.github.io/followupai-legal/

Privacy Policy:
https://jacobcarlisle.github.io/followupai-legal/privacy.html

Terms:
https://jacobcarlisle.github.io/followupai-legal/terms.html

Support:
https://jacobcarlisle.github.io/followupai-legal/support.html

Privacy Choices:
https://jacobcarlisle.github.io/followupai-legal/privacy-choices.html
```

Use the Privacy Policy URL and Support URL in App Store Connect. The Privacy Choices URL is optional, but useful if you want a dedicated page for data access/deletion instructions.
