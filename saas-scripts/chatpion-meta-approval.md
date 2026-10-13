> Full guide: [ChatPion App Review](https://singhamandeep.com/chatpion-app-review/)

---

# ChatPion Meta approval

ChatPion is a self-hosted Facebook and Instagram marketing script. The App Review submission is for the permissions that script calls, not for “ChatPion” as a product name Meta recognizes.

Full walkthrough: [ChatPion App Review](https://singhamandeep.com/chatpion-app-review/).

## Checklist

- [ ] The Meta app’s privacy policy URL and app domain match the domain where this ChatPion install is actually served.
- [ ] Facebook Login redirect URIs include the exact callback ChatPion uses, HTTPS, no stray slash mismatch.
- [ ] Only the permissions this install uses are in the submission. Extra Page permissions “from the docs zip” are a common rejection.
- [ ] A test Page is connected in ChatPion, and the test user can open the bot or inbox feature you describe.
- [ ] Webhook callback and verify token in the Meta app match the ChatPion settings screen.
- [ ] The screencast starts at the ChatPion login Meta was given, shows the Page connect, then one real message or post action for each permission in the submission.
- [ ] The video is the browser UI, not a screen of the Meta dashboard alone.

## Permissions you may be asked about

Typical installs touch `pages_messaging` and related Page permissions. Confirm the list on your own App Dashboard, then read [pages_messaging](../permissions/pages-messaging.md) and the [screencast checklist](../checklists/screencast-recording-checklist.md).

If ChatPion’s demo site is behind HTTP auth, put that username and password in the test-credentials field. A reviewer who hits a login wall rejects the whole submission.

## Policy citations (checked 3 October 2026)

These are the live documents. Do not cite an older section number as if it were still the heading.

- [Meta Developer Policies](https://developers.facebook.com/devpolicy/), last updated 3 February 2026. **Section 1, item 6** says: follow the instructions in the Developer Docs, including allowed usage for Platform. That is the current “1.6” line. A submission whose screencast does not match the allowed usage for the permission you asked for is rejected.
- Older enforcement mail sometimes said **“Developer Policy 1.9: use of a permission is not visible in the app.”** The 3 February 2026 policy text does not keep that section number. The test is unchanged: [App Review](https://developers.facebook.com/docs/app-review) must be able to open the app and see that permission used for its allowed purpose. If the reviewer cannot reach that screen, the whole submission can fail.
- [Platform Terms](https://developers.facebook.com/terms): Meta can require App Review, and approval does not replace ongoing compliance.
- [Permissions Reference](https://developers.facebook.com/documentation/development/permissions): use the exact permission name and its allowed usage. Facebook Login permissions and Instagram Login permissions are different families.
- [Messenger Platform policy](https://developers.facebook.com/documentation/business-messaging/messenger-platform/policy): opt-in, the 24-hour standard messaging window, and message tags.

Live service and case studies: [SinghAmandeep.com](https://singhamandeep.com/) and [case studies](https://singhamandeep.com/case-studies/). For a rejection that is already in cooldown, [message on WhatsApp](https://wa.me/917009556505).
