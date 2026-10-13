> Full guide: [Stackposts App Review](https://singhamandeep.com/stackposts-app-review/)

---

# Stackposts Instagram review

Stackposts schedules and publishes to social accounts. For Instagram, the permission that has to be visible is the publish permission your login product actually requests, most often `instagram_content_publish`.

Full walkthrough: [Stackposts App Review](https://singhamandeep.com/stackposts-app-review/).

## Checklist

- [ ] The live Stackposts URL in the Meta app settings is the install you will record, not a localhost or an old demo subdomain.
- [ ] Instagram is connected as a professional account inside Stackposts.
- [ ] The OAuth redirect URI saved at Meta matches Stackposts’ callback exactly.
- [ ] You publish one image post from Stackposts during the recording and show it live on Instagram.
- [ ] You do not demonstrate “import all my posts” or “backup this profile.” That conflicts with Instagram Platform policy.
- [ ] Each permission in the submission gets its own visible action. A single Facebook Page connect does not cover Instagram publish.
- [ ] Test credentials reach the Stackposts dashboard with no email-OTP the reviewer cannot receive. See [test credentials](../checklists/test-user-credentials-guide.md).

Publishing path details: [instagram_content_publish](../permissions/instagram-content-publish.md).

## Policy citations (checked 3 October 2026)

These are the live documents. Do not cite an older section number as if it were still the heading.

- [Meta Developer Policies](https://developers.facebook.com/devpolicy/), last updated 3 February 2026. **Section 1, item 6** says: follow the instructions in the Developer Docs, including allowed usage for Platform. That is the current “1.6” line. A submission whose screencast does not match the allowed usage for the permission you asked for is rejected.
- Older enforcement mail sometimes said **“Developer Policy 1.9: use of a permission is not visible in the app.”** The 3 February 2026 policy text does not keep that section number. The test is unchanged: [App Review](https://developers.facebook.com/docs/app-review) must be able to open the app and see that permission used for its allowed purpose. If the reviewer cannot reach that screen, the whole submission can fail.
- [Platform Terms](https://developers.facebook.com/terms): Meta can require App Review, and approval does not replace ongoing compliance.
- [Permissions Reference](https://developers.facebook.com/documentation/development/permissions): use the exact permission name and its allowed usage. Facebook Login permissions and Instagram Login permissions are different families.
- [Messenger Platform policy](https://developers.facebook.com/documentation/business-messaging/messenger-platform/policy): opt-in, the 24-hour standard messaging window, and message tags.

Live service and case studies: [SinghAmandeep.com](https://singhamandeep.com/) and [case studies](https://singhamandeep.com/case-studies/). For a rejection that is already in cooldown, [message on WhatsApp](https://wa.me/917009556505).
