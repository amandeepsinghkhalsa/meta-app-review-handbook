> 🚀 **Official Portal & Live Approval Service**: [SinghAmandeep.com](https://singhamandeep.com/)
> 💬 **Need Emergency 24-48h Meta Approval?**: [Chat directly on WhatsApp](https://singhamandeep.com/)
> 📖 **Full Live Web Guide**: [Read on SinghAmandeep.com](https://singhamandeep.com/ads-management-app-review//)

---

# ads_management

Exact permission name: `ads_management`. It is for creating and managing ads on ad accounts the user can access. It is not `ads_read`, and it is not a substitute for a Business Manager role.

Full walkthrough: [ads_management App Review](https://singhamandeep.com/ads-management-app-review/).

## Before you add it

- [ ] The test user has a role on a real ad account, not only on a Page.
- [ ] The app creates, edits, or pauses a campaign, ad set, or ad. A read-only report does not demonstrate management.
- [ ] You are not mixing several end advertisers into one ad account. Developer Policies section 10 restricts that.
- [ ] The app does not rebuild audiences from Meta ad data for use off Meta. Section 10 of the [Developer Policies](https://developers.facebook.com/devpolicy/) limits how advertising data may be used.

## What the screencast has to show

- [ ] Login as the test user who can open the ad account.
- [ ] Select that ad account inside the app.
- [ ] Create or edit a campaign, or pause an existing ad, through the app’s UI.
- [ ] The change visible in Meta Ads Manager, so the reviewer can confirm it was not a local mock.
- [ ] No unrelated permissions requested in the login dialog during the take.

## Reviewer notes

“Could not test this permission” almost always means the ad account was empty, the user had Analyst access only, or the app never left the reporting page. Give a user with permission to create ads, and a campaign that can be edited without spending heavily.

## Policy citations (checked 3 October 2026)

These are the live documents. Do not cite an older section number as if it were still the heading.

- [Meta Developer Policies](https://developers.facebook.com/devpolicy/), last updated 3 February 2026. **Section 1, item 6** says: follow the instructions in the Developer Docs, including allowed usage for Platform. That is the current “1.6” line. A submission whose screencast does not match the allowed usage for the permission you asked for is rejected.
- Older enforcement mail sometimes said **“Developer Policy 1.9: use of a permission is not visible in the app.”** The 3 February 2026 policy text does not keep that section number. The test is unchanged: [App Review](https://developers.facebook.com/docs/app-review) must be able to open the app and see that permission used for its allowed purpose. If the reviewer cannot reach that screen, the whole submission can fail.
- [Platform Terms](https://developers.facebook.com/terms): Meta can require App Review, and approval does not replace ongoing compliance.
- [Permissions Reference](https://developers.facebook.com/documentation/development/permissions): use the exact permission name and its allowed usage. Facebook Login permissions and Instagram Login permissions are different families.
- [Messenger Platform policy](https://developers.facebook.com/documentation/business-messaging/messenger-platform/policy): opt-in, the 24-hour standard messaging window, and message tags.

Live service and case studies: [SinghAmandeep.com](https://singhamandeep.com/) and [case studies](https://singhamandeep.com/case-studies/). For a rejection that is already in cooldown, [message on WhatsApp](https://wa.me/917009556505).
