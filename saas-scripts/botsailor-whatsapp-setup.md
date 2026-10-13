> Full guide: [BotSailor App Review](https://singhamandeep.com/botsailor-app-review/)

---

# BotSailor WhatsApp setup

BotSailor sits on the WhatsApp Cloud API. App Review, Business Verification, and the webhook are three different gates. Passing one does not pass the others.

Full walkthrough: [BotSailor App Review](https://singhamandeep.com/botsailor-app-review/).

## Checklist

- [ ] The Meta app, WhatsApp product, and BotSailor install use the same app id.
- [ ] Webhook callback URL is the BotSailor HTTPS endpoint, and the verify token matches.
- [ ] A test number is added. You can send a WhatsApp message to it from a phone the reviewer can also use, or you provide a working test path.
- [ ] `whatsapp_business_messaging` is the permission you demonstrate, with the flow in [that checklist](../permissions/whatsapp-business-messaging.md).
- [ ] The screencast shows an inbound message in BotSailor and a reply leaving BotSailor, then the phone.
- [ ] Template status is not the story of the video. A template can be pending and the session reply can still be the demonstration.
- [ ] Business Verification documents match the legal name on the WhatsApp display name.

## What not to submit as the use case

Do not file the use case as “fix my template rejection” or “this phone is already on the WhatsApp Business app.” Those are not the allowed usage of `whatsapp_business_messaging`.

## Policy citations (checked 3 October 2026)

These are the live documents. Do not cite an older section number as if it were still the heading.

- [Meta Developer Policies](https://developers.facebook.com/devpolicy/), last updated 3 February 2026. **Section 1, item 6** says: follow the instructions in the Developer Docs, including allowed usage for Platform. That is the current “1.6” line. A submission whose screencast does not match the allowed usage for the permission you asked for is rejected.
- Older enforcement mail sometimes said **“Developer Policy 1.9: use of a permission is not visible in the app.”** The 3 February 2026 policy text does not keep that section number. The test is unchanged: [App Review](https://developers.facebook.com/docs/app-review) must be able to open the app and see that permission used for its allowed purpose. If the reviewer cannot reach that screen, the whole submission can fail.
- [Platform Terms](https://developers.facebook.com/terms): Meta can require App Review, and approval does not replace ongoing compliance.
- [Permissions Reference](https://developers.facebook.com/documentation/development/permissions): use the exact permission name and its allowed usage. Facebook Login permissions and Instagram Login permissions are different families.
- [Messenger Platform policy](https://developers.facebook.com/documentation/business-messaging/messenger-platform/policy): opt-in, the 24-hour standard messaging window, and message tags.

Live service and case studies: [SinghAmandeep.com](https://singhamandeep.com/) and [case studies](https://singhamandeep.com/case-studies/). For a rejection that is already in cooldown, [message on WhatsApp](https://wa.me/917009556505).
