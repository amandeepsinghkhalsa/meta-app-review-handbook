> Full guide: [human_agent App Review](https://singhamandeep.com/human-agent-app-review/)

---

# human_agent

Exact permission name: `human_agent`. It is not a standalone inbox permission. It extends the window in which a human on your team can reply after a person messages the Page. Meta expects `pages_messaging` (or the Instagram messaging permission you actually use) to already make sense in the same app.

Full walkthrough: [human_agent App Review](https://singhamandeep.com/human-agent-app-review/).

## Before you add it

- [ ] The app already demonstrates a human taking over a conversation. A bot-only flow does not justify `human_agent`.
- [ ] You are not using the human-agent tag to send broadcasts, promos, or daily deals. That is outside the tag’s purpose in the [Messenger policy](https://developers.facebook.com/documentation/business-messaging/messenger-platform/policy).
- [ ] The test user can switch from the automated reply to a named human agent in the UI.
- [ ] The submission text says a person is replying, and the video shows that person.

## What the screencast has to show

- [ ] A customer message arriving.
- [ ] The conversation leaving the bot and landing in a human queue.
- [ ] A human agent sending the reply from inside the app, after the standard window would have closed, if that is the feature you claim.
- [ ] The reply visible on the Page or Instagram thread.
- [ ] No claim on screen that the tag is used for marketing.

## Reviewer notes

The usual rejection is “the use of the permission is not visible.” The reviewer saw a bot reply and never saw a human. Record the handoff. If `pages_messaging` is not approved or not in the same submission with a working inbox, fix that first: [pages_messaging](https://singhamandeep.com/pages-messaging-app-review/).

## Policy citations (checked 3 October 2026)

These are the live documents. Do not cite an older section number as if it were still the heading.

- [Meta Developer Policies](https://developers.facebook.com/devpolicy/), last updated 3 February 2026. **Section 1, item 6** says: follow the instructions in the Developer Docs, including allowed usage for Platform. That is the current “1.6” line. A submission whose screencast does not match the allowed usage for the permission you asked for is rejected.
- Older enforcement mail sometimes said **“Developer Policy 1.9: use of a permission is not visible in the app.”** The 3 February 2026 policy text does not keep that section number. The test is unchanged: [App Review](https://developers.facebook.com/docs/app-review) must be able to open the app and see that permission used for its allowed purpose. If the reviewer cannot reach that screen, the whole submission can fail.
- [Platform Terms](https://developers.facebook.com/terms): Meta can require App Review, and approval does not replace ongoing compliance.
- [Permissions Reference](https://developers.facebook.com/documentation/development/permissions): use the exact permission name and its allowed usage. Facebook Login permissions and Instagram Login permissions are different families.
- [Messenger Platform policy](https://developers.facebook.com/documentation/business-messaging/messenger-platform/policy): opt-in, the 24-hour standard messaging window, and message tags.

Live service and case studies: [SinghAmandeep.com](https://singhamandeep.com/) and [case studies](https://singhamandeep.com/case-studies/). For a rejection that is already in cooldown, [message on WhatsApp](https://wa.me/917009556505).
