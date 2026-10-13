> Full guide: [whatsapp_business_messaging App Review](https://singhamandeep.com/whatsapp-business-messaging-app-review/)

---

# whatsapp_business_messaging

Exact permission name: `whatsapp_business_messaging`. It covers sending and receiving WhatsApp messages for a WhatsApp Business Account through the Cloud API. It does not approve message templates, and it does not fix a phone number that is already registered on the WhatsApp Business app.

Full walkthrough: [whatsapp_business_messaging App Review](https://singhamandeep.com/whatsapp-business-messaging-app-review/). Business Verification is a separate process and is in scope when Meta asks for it: [SinghAmandeep.com](https://singhamandeep.com/).

## Before you add it

- [ ] A WhatsApp Business Account is connected to the app, with a test number the reviewer can message.
- [ ] The webhook is verified, HTTPS, and returns 200 for inbound messages.
- [ ] You know which messages are session messages and which need an approved template. Do not demonstrate a cold promotional blast.
- [ ] The display name and business match what the reviewer will see on the phone.

## What the screencast has to show

- [ ] A test user sending a WhatsApp message to the business number.
- [ ] That message arriving in the app.
- [ ] The app sending a reply.
- [ ] The reply visible on the phone.
- [ ] The webhook or logs only if they help the reviewer see the same message id. Do not spend the video on server config.

## Reviewer notes

Template rejection appeals and “phone number already registered” troubleshooting are not this permission. Do not describe them as the use case. The allowed demonstration is a business conversation the Cloud API actually sends.

## Policy citations (checked 3 October 2026)

These are the live documents. Do not cite an older section number as if it were still the heading.

- [Meta Developer Policies](https://developers.facebook.com/devpolicy/), last updated 3 February 2026. **Section 1, item 6** says: follow the instructions in the Developer Docs, including allowed usage for Platform. That is the current “1.6” line. A submission whose screencast does not match the allowed usage for the permission you asked for is rejected.
- Older enforcement mail sometimes said **“Developer Policy 1.9: use of a permission is not visible in the app.”** The 3 February 2026 policy text does not keep that section number. The test is unchanged: [App Review](https://developers.facebook.com/docs/app-review) must be able to open the app and see that permission used for its allowed purpose. If the reviewer cannot reach that screen, the whole submission can fail.
- [Platform Terms](https://developers.facebook.com/terms): Meta can require App Review, and approval does not replace ongoing compliance.
- [Permissions Reference](https://developers.facebook.com/documentation/development/permissions): use the exact permission name and its allowed usage. Facebook Login permissions and Instagram Login permissions are different families.
- [Messenger Platform policy](https://developers.facebook.com/documentation/business-messaging/messenger-platform/policy): opt-in, the 24-hour standard messaging window, and message tags.

Live service and case studies: [SinghAmandeep.com](https://singhamandeep.com/) and [case studies](https://singhamandeep.com/case-studies/). For a rejection that is already in cooldown, [message on WhatsApp](https://wa.me/917009556505).
