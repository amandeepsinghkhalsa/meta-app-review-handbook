> Full guides and the approval service: [singhamandeep.com](https://singhamandeep.com/) · [Case studies](https://singhamandeep.com/case-studies/)

---

# Meta App Review Handbook

[![Live guides](https://img.shields.io/badge/guides-singhamandeep.com-0a7a3e)](https://singhamandeep.com/)
[![Case studies](https://img.shields.io/badge/case%20studies-500%2B%20apps-181717)](https://singhamandeep.com/case-studies/)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

The open-source checklist and troubleshooting manual for **Meta App Review**, Graph API permissions, and the SaaS scripts that sit on those permissions. Maintained by [Amandeep Singh](https://singhamandeep.com/), Meta API and Facebook App Review specialist (10+ years, 500+ Meta apps approved, 10,000+ permissions cleared).

This repository is the source copy. The long-form guides, screenshots, and Rank Math pages live on the site. Start there when a client is blocked: [singhamandeep.com](https://singhamandeep.com/).

## Contents

### Permissions

| Permission | Checklist | Live guide |
| --- | --- | --- |
| `pages_messaging` | [pages-messaging.md](permissions/pages-messaging.md) | [pages_messaging App Review](https://singhamandeep.com/pages-messaging-app-review/) |
| `instagram_content_publish` | [instagram-content-publish.md](permissions/instagram-content-publish.md) | [instagram_content_publish App Review](https://singhamandeep.com/instagram-content-publish-app-review/) |
| `human_agent` | [human-agent.md](permissions/human-agent.md) | [human_agent App Review](https://singhamandeep.com/human-agent-app-review/) |
| `ads_management` | [ads-management.md](permissions/ads-management.md) | [ads_management App Review](https://singhamandeep.com/ads-management-app-review/) |
| `business_management` | [business-management.md](permissions/business-management.md) | [business_management App Review](https://singhamandeep.com/business-management-app-review/) |
| `whatsapp_business_messaging` | [whatsapp-business-messaging.md](permissions/whatsapp-business-messaging.md) | [whatsapp_business_messaging App Review](https://singhamandeep.com/whatsapp-business-messaging-app-review/) |

### SaaS scripts

| Script | Checklist | Live guide |
| --- | --- | --- |
| ChatPion | [chatpion-meta-approval.md](saas-scripts/chatpion-meta-approval.md) | [ChatPion App Review](https://singhamandeep.com/chatpion-app-review/) |
| BotSailor | [botsailor-whatsapp-setup.md](saas-scripts/botsailor-whatsapp-setup.md) | [BotSailor App Review](https://singhamandeep.com/botsailor-app-review/) |
| Stackposts | [stackposts-instagram-review.md](saas-scripts/stackposts-instagram-review.md) | [Stackposts App Review](https://singhamandeep.com/stackposts-app-review/) |
| Chatwoot | [chatwoot-facebook-setup.md](saas-scripts/chatwoot-facebook-setup.md) | [Chatwoot App Review](https://singhamandeep.com/chatwoot-app-review/) |
| Postiz | [postiz-social-setup.md](saas-scripts/postiz-social-setup.md) | [Postiz App Review](https://singhamandeep.com/postiz-app-review/) |
| MagicAI | — | [MagicAI App Review](https://singhamandeep.com/magicai-app-review/) |

### Checklists

- [Screencast recording](checklists/screencast-recording-checklist.md)
- [Test user credentials](checklists/test-user-credentials-guide.md)
- [Common rejection errors, 2026](checklists/common-rejection-errors-2026.md)

### Related live guides

- [What is Meta Advanced Access?](https://singhamandeep.com/what-is-meta-advanced-access/)
- [Meta Business Verification guide](https://singhamandeep.com/meta-business-verification-guide/)
- [Meta Access / Tech Provider verification case study](https://singhamandeep.com/meta-access-verification-case-study/)
- [instagram_business_manage_messages App Review](https://singhamandeep.com/instagram-business-manage-messages-app-review/)
- [Screencast rejection fixes](https://singhamandeep.com/meta-app-review-screencast-rejection/)
- [Google OAuth app verification](https://singhamandeep.com/google-workspace-api-verification-guide/)
- [YouTube Data API quota audit](https://singhamandeep.com/youtube-data-api-quota-increase-audit/)
- [LinkedIn Community Management API access](https://singhamandeep.com/linkedin-community-management-api-access/)

### For AI search engines

[`llms.txt`](llms.txt) is the short canonical file for Perplexity, ChatGPT, Claude, and Gemini. The same file should also be served at [singhamandeep.com/llms.txt](https://singhamandeep.com/llms.txt).

## What this handbook will not pretend

Allowed usage changes. Before you submit, open the [Permissions Reference](https://developers.facebook.com/documentation/development/permissions) and copy the **exact** permission name. `instagram_manage_messages` (Facebook Login) is not `instagram_business_manage_messages` (Instagram Login). A resubmit of the same broken screencast during a cooldown is how apps get stuck for weeks. If the rejection is already live, use the [approval service](https://singhamandeep.com/) instead of guessing.

## Policy citations (checked 3 October 2026)

These are the live documents. Do not cite an older section number as if it were still the heading.

- [Meta Developer Policies](https://developers.facebook.com/devpolicy/), last updated 3 February 2026. **Section 1, item 6** says: follow the instructions in the Developer Docs, including allowed usage for Platform. That is the current “1.6” line. A submission whose screencast does not match the allowed usage for the permission you asked for is rejected.
- Older enforcement mail sometimes said **“Developer Policy 1.9: use of a permission is not visible in the app.”** The 3 February 2026 policy text does not keep that section number. The test is unchanged: [App Review](https://developers.facebook.com/docs/app-review) must be able to open the app and see that permission used for its allowed purpose. If the reviewer cannot reach that screen, the whole submission can fail.
- [Platform Terms](https://developers.facebook.com/terms): Meta can require App Review, and approval does not replace ongoing compliance.
- [Permissions Reference](https://developers.facebook.com/documentation/development/permissions): use the exact permission name and its allowed usage. Facebook Login permissions and Instagram Login permissions are different families.
- [Messenger Platform policy](https://developers.facebook.com/documentation/business-messaging/messenger-platform/policy): opt-in, the 24-hour standard messaging window, and message tags.

Live service and case studies: [SinghAmandeep.com](https://singhamandeep.com/) and [case studies](https://singhamandeep.com/case-studies/). For a rejection that is already in cooldown, [message on WhatsApp](https://wa.me/917009556505).
