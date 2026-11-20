# Ilu Reader Privacy Policy

**Operator:** Ilu Reader project

**Contact:** vasily.bakshaev@gmail.com

**Publication:** https://vasilybakshaev.github.io/ilu-reader-legal/privacy-policy.html

**Effective date:** November 23, 2026

## 1. In brief

Ilu Reader is a book reader with tap-to-translate. Books, settings, reading
progress and word cards are stored on the device. Only the requests needed for AI
translation, subscription checks and loading the Cloud catalog are sent online.

## 2. What data is processed

**On the device:** books, settings, reading progress, book language, word cards,
translation cache and a random device identifier (16 random bytes; no name, email
or phone number).

**On our server (for AI translation):** device identifier, word, context sentence
and translation languages. The identifier is used only for limits and
subscriptions and is not sent to the AI service. The word and sentence are not
stored after the response — only request counters remain.

**Subscription:** subscription status is processed through RevenueCat, payment —
through the App Store or Google Play. We do not receive bank card data.

**Technical data:** IP address and standard HTTP headers are visible to Cloudflare
(hosting), RevenueCat, the AI provider and GitHub (Cloud catalog).

We do not collect names, email, phone numbers, location, contacts, photos or
advertising identifiers, do not show ads and do not track users across apps and
websites.

## 3. Why

- operation of the reader, on-device translation and cards;
- AI translation of a word in context and limit accounting;
- subscription checks;
- protecting the server from spam and abuse;
- responding to support requests.

## 4. Who receives data

| Recipient | What it receives | Why |
|---|---|---|
| Cloudflare | translation request, counters, device identifier | server hosting |
| AI provider (DeepSeek; OpenRouter possible) | word, sentence, languages — **without the identifier** | translation |
| RevenueCat | device identifier, subscription status | subscription management |
| Apple / Google | purchase data | payment and subscription management |
| GitHub | request IP address | Cloud catalog |

Data is not sold and is not used for advertising.

## 5. Retention

| Data | Period |
|---|---|
| Limit counters | 2 days |
| Subscription status cache | 5 minutes |
| Translation cache (not cards) | 30 days |
| Word cards, books, settings, progress | until deleted in the app |

## 6. Your rights

Local data is deleted together with the app. Server data (counters, subscription
cache, RevenueCat record) is deleted on request to vasily.bakshaev@gmail.com; we reply within 30
days.

## 7. Children

The app is not intended for children under 12 and does not collect age data.

## 8. On-device mode

If translation on the device is enabled in Settings, the word and sentence are not sent
to our server or the AI: translation runs on the device. Requests to the Cloud
catalog and subscription checks may still be performed.

## 9. Changes

A new version is published at https://vasilybakshaev.github.io/ilu-reader-legal/privacy-policy.html and in the app; the effective date is shown
at the beginning of the document.

## 10. Contacts

Ilu Reader project · vasily.bakshaev@gmail.com · https://vasilybakshaev.github.io/ilu-reader-legal
