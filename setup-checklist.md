# Setup checklist

Complete this before you launch the first test. Most failed tests fail here: a disconnected WhatsApp number, no one replying, or no way to see which ad a chat came from.

## 1. Accounts and access

- [ ] **Meta Business portfolio** (Business Manager) owns the Facebook Page, Instagram account and ad account
- [ ] Everyone who runs ads has their own login with the right role (no shared passwords)
- [ ] **Payment method** added to the ad account, with a spending limit set
- [ ] Ad account **currency and time zone** are correct (these can't be changed later without a new account)
- [ ] Two-factor authentication on for every admin

## 2. Message destinations

**WhatsApp**
- [ ] A **WhatsApp Business** number (app or platform) that someone will actually answer
- [ ] The WhatsApp account is **connected to the Facebook Page** (Page settings → Linked accounts → WhatsApp)
- [ ] Business profile filled in: name, logo, description, hours, website
- [ ] **Greeting message** and **away message** set (templates in [`whatsapp-reply-scripts.md`](whatsapp-reply-scripts.md))
- [ ] Quick replies saved for the common questions

**Messenger and Instagram Direct**
- [ ] Page and Instagram inboxes are checked in **Meta Business Suite → Inbox** by a named person
- [ ] Instant reply and FAQs set up in the inbox automations

**Response time**
- [ ] A named person replies **within 15 minutes** during business hours. Fast replies turn far more chats into calls than slow ones.

## 3. Tracking

- [ ] Every ad has a clear name following the [naming convention](campaign-structure.md#naming-convention), so you can see which hook each chat came from
- [ ] Ad-specific **pre-filled message** or ice-breaker question, so you can tell which ad started a chat (e.g. "Hi! I'd like to know about the free hardware offer")
- [ ] A shared **results log** ready: [`message-testing-workbook.xlsx`](message-testing-workbook.xlsx) or your CRM
- [ ] A way to log what happened next: qualified? demo booked? customer?
- [ ] If you also send traffic to a website: Meta Pixel and Conversions API set up, and URL parameters added (see the [UTM kit](https://github.com/shahshivani120-lab/b2b-utm-ga4-lead-tracking))

## 4. Audience

- [ ] Location set precisely (country, region or city radius)
- [ ] Age range matches buyers (e.g. 25–65 for business owners)
- [ ] One **fixed audience** for the whole test (don't change it between ads)
- [ ] Decide: broad targeting (let Meta find buyers) or interests/job-related targeting. Keep the same choice for every ad in the test
- [ ] Exclude existing customers if you can (upload a customer list as a custom audience)

## 5. Creative

- [ ] One [creative brief](creative-brief.md) per ad
- [ ] Images: 1080 × 1080 (feed) and 1080 × 1920 (Stories/Reels) versions
- [ ] Text on the image is short and readable on a phone
- [ ] Every ad has the **hook in the first line** of the primary text
- [ ] Brand, offer and price checked by the business owner

## 6. Pre-launch check (5 minutes)

- [ ] Send a test message from your own phone through each ad preview. Does it arrive? Does the greeting fire?
- [ ] Check the daily budget on every ad set (watch for an extra zero)
- [ ] Check start and end dates
- [ ] Check placements are the same for every ad in the test
- [ ] Screenshot the setup for your records
