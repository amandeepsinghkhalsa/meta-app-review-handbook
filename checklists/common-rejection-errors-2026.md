> Full guide: [Meta App Review rejection fixes](https://singhamandeep.com/meta-app-review-rejection-fix/)

---

# Common rejection errors, 2026

Names below are the ones Meta’s reviewers still use. The fix is always “make the allowed use visible,” not a longer essay in the notes box.

## Inadequate demonstration

The reviewer opened the app and could not see the permission used. Typical causes: the video shows the Meta dashboard, the button was never clicked, or the result never appeared on Messenger, Instagram, Ads Manager, or WhatsApp.

Fix: re-record with the [screencast checklist](screencast-recording-checklist.md). Do not resubmit the same file.

## Disallowed use case

The written use does not match the allowed usage for that exact permission name. Backup tools, follower tools, and “we need all Page permissions for later” fall here. Read the [Permissions Reference](https://developers.facebook.com/documentation/development/permissions) and delete every permission you cannot show.

## Use of the permission is not visible

This is the rejection older mail called Developer Policy 1.9. The 3 February 2026 [Developer Policies](https://developers.facebook.com/devpolicy/) no longer use that number. Section 1, item 6 is the current allowed-usage line. The practical meaning is unchanged: the feature must be on screen.

## Could not test the app

Login failed, 2FA blocked them, the server was down, or the test user had no role on the asset. Fix credentials using the [credentials guide](test-user-credentials-guide.md) before you think about the screencast.

## Wrong permission family

`instagram_manage_messages` and `instagram_business_manage_messages` are not interchangeable. Facebook Login and Instagram Login do not share a permission list. Submitting the cousin permission is an automatic mismatch.

## Cooldown

A rejected permission should not be filed again with the same video and the same notes. Change the demonstration, wait out the period Meta states in the rejection, then submit. Repeating the same package is how a one-week fix becomes a month.

## Screencast of the wrong product

For ChatPion, BotSailor, Stackposts, Chatwoot, and Postiz, the UI in the video must be that install. A generic Meta screen recording does not transfer.

When the rejection is already in the dashboard and you want it recovered: [SinghAmandeep.com](https://singhamandeep.com/) or [WhatsApp](https://wa.me/917009556505).

## Policy citations (checked 3 October 2026)

These are the live documents. Do not cite an older section number as if it were still the heading.

- [Meta Developer Policies](https://developers.facebook.com/devpolicy/), last updated 3 February 2026. **Section 1, item 6** says: follow the instructions in the Developer Docs, including allowed usage for Platform. That is the current “1.6” line. A submission whose screencast does not match the allowed usage for the permission you asked for is rejected.
- Older enforcement mail sometimes said **“Developer Policy 1.9: use of a permission is not visible in the app.”** The 3 February 2026 policy text does not keep that section number. The test is unchanged: [App Review](https://developers.facebook.com/docs/app-review) must be able to open the app and see that permission used for its allowed purpose. If the reviewer cannot reach that screen, the whole submission can fail.
- [Platform Terms](https://developers.facebook.com/terms): Meta can require App Review, and approval does not replace ongoing compliance.
- [Permissions Reference](https://developers.facebook.com/documentation/development/permissions): use the exact permission name and its allowed usage. Facebook Login permissions and Instagram Login permissions are different families.
- [Messenger Platform policy](https://developers.facebook.com/documentation/business-messaging/messenger-platform/policy): opt-in, the 24-hour standard messaging window, and message tags.

Live service and case studies: [SinghAmandeep.com](https://singhamandeep.com/) and [case studies](https://singhamandeep.com/case-studies/). For a rejection that is already in cooldown, [message on WhatsApp](https://wa.me/917009556505).
