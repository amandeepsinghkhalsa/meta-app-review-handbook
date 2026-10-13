> Full guide: [instagram_content_publish App Review](https://singhamandeep.com/instagram-content-publish-app-review/)

---

# instagram_content_publish

Exact permission name: `instagram_content_publish`. It is for publishing content to an Instagram professional account through the Instagram Graph API. It is not the permission for reading the inbox, and it is not `instagram_business_content_publish` if your app uses Instagram Login. Check the login product on the app before you type the name.

Full walkthrough: [instagram_content_publish App Review](https://singhamandeep.com/instagram-content-publish-app-review/).

## Before you add it

- [ ] The Instagram account is Professional (Business or Creator) and linked the way your login product requires.
- [ ] The app calls the Content Publishing endpoints, not a “download my posts” backup flow. Display-only use is outside allowed usage.
- [ ] The test account can open the composer your app actually ships.
- [ ] Media you publish in the recording is content you have rights to. Do not publish a random scraped Reel.

## What the screencast has to show

- [ ] Login as the test user supplied to Meta.
- [ ] Create or select an image or video inside the app.
- [ ] The publish action, then the container moving to published.
- [ ] The new post visible on the Instagram professional account.
- [ ] The permission name in the submission matches the login product on screen.

## Reviewer notes

[Instagram Platform policy, section 6](https://developers.facebook.com/devpolicy/) says you may not use the Instagram Platform only to display user content, import or back up content, or manage relationships, without prior permission. A scheduler that never publishes, or a screen recording of the Meta dashboard, fails that test.

If the app is a multi-tenant script (Stackposts, Postiz, and similar), the recording still has to be that script’s own UI, not a generic Instagram screen. See [Stackposts](../saas-scripts/stackposts-instagram-review.md) and [Postiz](../saas-scripts/postiz-social-setup.md).

## Policy citations (checked 3 October 2026)

These are the live documents. Do not cite an older section number as if it were still the heading.

- [Meta Developer Policies](https://developers.facebook.com/devpolicy/), last updated 3 February 2026. **Section 1, item 6** says: follow the instructions in the Developer Docs, including allowed usage for Platform. That is the current “1.6” line. A submission whose screencast does not match the allowed usage for the permission you asked for is rejected.
- Older enforcement mail sometimes said **“Developer Policy 1.9: use of a permission is not visible in the app.”** The 3 February 2026 policy text does not keep that section number. The test is unchanged: [App Review](https://developers.facebook.com/docs/app-review) must be able to open the app and see that permission used for its allowed purpose. If the reviewer cannot reach that screen, the whole submission can fail.
- [Platform Terms](https://developers.facebook.com/terms): Meta can require App Review, and approval does not replace ongoing compliance.
- [Permissions Reference](https://developers.facebook.com/documentation/development/permissions): use the exact permission name and its allowed usage. Facebook Login permissions and Instagram Login permissions are different families.
- [Messenger Platform policy](https://developers.facebook.com/documentation/business-messaging/messenger-platform/policy): opt-in, the 24-hour standard messaging window, and message tags.

Live service and case studies: [SinghAmandeep.com](https://singhamandeep.com/) and [case studies](https://singhamandeep.com/case-studies/). For a rejection that is already in cooldown, [message on WhatsApp](https://wa.me/917009556505).
