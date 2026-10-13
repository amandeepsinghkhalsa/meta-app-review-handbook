> Full guide: [Fixing "test credentials do not work" rejections](https://singhamandeep.com/meta-rejection-test-credentials-do-not-work/)

---

# Test user credentials

If the reviewer cannot log in, every permission in that submission is rejected. Credentials are part of the review, not a courtesy.

## What to put in the instructions field

- [ ] App URL, including https.
- [ ] Username and password for a user who can reach the feature. If the password contains symbols, paste it in a plain line, not a screenshot.
- [ ] A second account when the flow needs one (the person who messages the Page, or the customer WhatsApp number).
- [ ] Which Page, Instagram account, ad account, or WhatsApp number to open, by name.
- [ ] 2FA disabled on that test user, or a method the reviewer can complete without your phone. An authenticator only you hold will fail the review.
- [ ] Any HTTP basic-auth in front of a staging site, in the same instructions.

## What not to do

- [ ] Do not send the reviewer your personal Facebook login.
- [ ] Do not depend on an email or SMS OTP to a number you control.
- [ ] Do not expire the password or rotate the webhook token while the review is open.
- [ ] Do not give a user who lacks a role on the Page or ad account you told them to test.

## After you submit

- [ ] Log in yourself with the same instructions, in a private window, and time how many clicks it takes to reach the feature.
- [ ] Leave the test data in place until the review closes. Deleting the demo Page mid-review is a failed test.

If a previous review died at login, say so in the notes and point at the fixed path. The [approval desk](https://singhamandeep.com/) handles this when the cooldown is already running.

## Policy citations (checked 3 October 2026)

These are the live documents. Do not cite an older section number as if it were still the heading.

- [Meta Developer Policies](https://developers.facebook.com/devpolicy/), last updated 3 February 2026. **Section 1, item 6** says: follow the instructions in the Developer Docs, including allowed usage for Platform. That is the current “1.6” line. A submission whose screencast does not match the allowed usage for the permission you asked for is rejected.
- Older enforcement mail sometimes said **“Developer Policy 1.9: use of a permission is not visible in the app.”** The 3 February 2026 policy text does not keep that section number. The test is unchanged: [App Review](https://developers.facebook.com/docs/app-review) must be able to open the app and see that permission used for its allowed purpose. If the reviewer cannot reach that screen, the whole submission can fail.
- [Platform Terms](https://developers.facebook.com/terms): Meta can require App Review, and approval does not replace ongoing compliance.
- [Permissions Reference](https://developers.facebook.com/documentation/development/permissions): use the exact permission name and its allowed usage. Facebook Login permissions and Instagram Login permissions are different families.
- [Messenger Platform policy](https://developers.facebook.com/documentation/business-messaging/messenger-platform/policy): opt-in, the 24-hour standard messaging window, and message tags.

Live service and case studies: [SinghAmandeep.com](https://singhamandeep.com/) and [case studies](https://singhamandeep.com/case-studies/). For a rejection that is already in cooldown, [message on WhatsApp](https://wa.me/917009556505).
