# Upfront Privacy Policy

Effective November 14, 2026

Upfront is an app for planning and tracking sales pursuits. This policy explains what the app does with your information. The short version: your data stays on your device, or in your own iCloud account if you turn on sync, and goes to Anthropic only when you use an AI feature with your own API key. The developer never receives it.

## What Upfront stores, and where

Everything you enter in Upfront stays in the app on your device. That includes companies, sites, people, pursuits, meetings, notes, commitments, meeting plans, transcripts you import, and debriefs.

If you turn on iCloud sync, Upfront keeps a copy in your own private iCloud database, so your other devices signed in to the same Apple account can see it. Apple stores that data under its own terms and privacy policy. The developer can't see or access your iCloud data.

Builds distributed through TestFlight may have iCloud sync turned off. Then your data stays only on the device where you entered it.

## AI features

Some features, such as meeting plans, quick reads, follow-up extraction and transcript debriefs, use an AI model from Anthropic. These features only run when you ask for them. They need an Anthropic API key, which you enter yourself.

- **Your key** is stored in your device's Keychain. It isn't synced through iCloud or sent anywhere except to Anthropic with each request.
- **What's sent:** the content you ask the app to process (for example, an email, your notes, or a meeting transcript), plus the details of the pursuit it relates to, such as company and site names, people's names and titles, the roles and assessments you've recorded for them, your stage evidence, commitments, and recent and upcoming meetings. The email addresses and phone numbers stored on people's records aren't sent, and neither are the notes you keep on people, companies, sites or meetings. Anything inside the content itself, such as a signature block in an email you share, is sent as part of that content.
- **Where it goes:** directly from your device to Anthropic's API, under the account that owns the API key. Anthropic handles that data under its own terms and privacy policy.
- **Without a key,** nothing is sent. If you try an AI feature without one, the app says a key is needed and records the attempt on your device.

The app keeps a record of each AI request on your device (and in your iCloud, if sync is on), including its cost and the text sent and received, so you can review your usage. It keeps the newest 200 records: each time the app starts, older ones are deleted, except the latest of each kind for a pursuit and those a meeting plan or debrief was made from. Monthly cost totals are kept. When you delete a meeting, pursuit or company, the text of the requests used only for what you deleted is cleared and their cost is kept.

## Contacts

You can add one person at a time without giving Upfront access to your contacts: by choosing them from your contacts, sharing a contact card, dragging a card into the app, or pasting one on a Mac. Only that card is read.

Upfront asks for access to your contacts only if you use one of these:

- **Open in Contacts** or **Update from iPhone Contacts** on a person you've linked to a card. Upfront reads only that card.
- **Contact matching** in Settings, off by default. It searches your contacts for each person you add, by email, phone or name, and links a match. If there's no match, it adds a new card to your contacts. If you change a linked person's title, email or phone, it asks before updating their card.

Nothing read from your contacts is sent to the AI model.

## What the developer receives

Nothing. Upfront has no analytics, no advertising and no tracking, and it doesn't send your data to the developer or to any third party other than Anthropic (for the AI features you use) and Apple (for iCloud sync, if you turn it on).

If you install Upfront through TestFlight, Apple may share crash reports and any feedback you choose to send with the developer, under Apple's TestFlight terms.

## Deleting your data

- Delete individual records in the app. Deletes also apply on your other synced devices.
- Deleting the app removes the data stored on that device. iOS may keep your API key in the Keychain after the app is deleted, so remove it first in Settings with Remove Key.
- To remove synced data from iCloud, turn sync off in Upfront's Settings, iCloud Sync, and use Delete iCloud Copy. You can also use your device's iCloud settings to manage Upfront's stored data.
- AI requests already sent to Anthropic are governed by Anthropic's terms for the account that owns the API key.

## Children

Upfront is a business tool and isn't directed at children.

## Changes

If this policy changes, the updated version will be posted at this address with a new effective date.

## Contact

Questions about this policy: jpayne@hargrove-epc.com
