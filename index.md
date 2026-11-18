# Upfront Privacy Policy

Effective November 17, 2026

Upfront is an app for planning and tracking sales pursuits. This policy explains what the app does with your information. The short version: your data stays on your device, or in your own iCloud account if you turn on sync, and goes to Anthropic only when you use an AI feature with your own API key. The developer never receives it.

## What Upfront stores, and where

Everything you enter in Upfront stays in the app on your device. That includes companies, sites, people, pursuits and prospects, meetings, notes, commitments, meeting plans, readings and objections, transcripts you import, debriefs, the speaker names Upfront remembers for each company, and a saved review of each debrief or follow-up showing what the AI suggested, what you kept and what you didn't keep.

Some things stay only on the device where you entered them and are never synced: your name, which you enter when Upfront first opens or in Settings; emails, transcripts and contact cards you share to Upfront, which wait there until you log or remove them and are deleted after 30 days with one notice; the list of your open pursuits and people (names, email addresses and companies) that the share sheet uses to suggest where a shared item belongs; debriefs waiting for your review; and reminders, which are notifications on the device.

If you turn on iCloud sync, Upfront keeps a copy in your own private iCloud database, so your other devices signed in to the same Apple account can see it. When sync is on, Upfront also records in your iCloud which of your devices sends reminders. Apple stores that data under its own terms and privacy policy. The developer can't see or access your iCloud data.

iCloud sync is off unless you turn it on in Settings, iCloud Sync. While it's off, your data stays only on the device where you entered it.

## AI features

Some features, such as meeting plans, quick reads, follow-up extraction and transcript debriefs, use an AI model from Anthropic. These features only run when you ask for them. They need an Anthropic API key, which you enter yourself.

- **Your key** is stored in your device's Keychain. It isn't synced through iCloud or sent anywhere except to Anthropic with each request.
- **What's sent:** the content you ask the app to process (for example, an email, your notes, or a meeting transcript), plus the details of the pursuit it relates to, such as company and site names, people's names and titles, the roles and assessments you've recorded for them, your stage evidence, commitments, and recent and upcoming meetings. A follow-up also sends the names and titles of the people you've recorded at that company, and your name and firm. A debrief also sends your name and firm, the meeting's attendees, who ran it, its planned and actual length, its meeting plan, the notes you typed on that meeting's call card, your note on what happened after a recording stopped, and each speaker with their company or, for a colleague, their division. Email addresses and phone numbers in the content are replaced with placeholders before it's sent. The email addresses and phone numbers stored on people's records aren't sent, and neither are the notes you keep on people, companies and sites, or a meeting's other notes.
- **Where it goes:** directly from your device to Anthropic's API, under the account that owns the API key. Anthropic handles that data under its own terms and privacy policy.
- **Without a key,** nothing is sent. If you try an AI feature without one, the app says a key is needed and records the attempt on your device.

The app keeps a record of each AI request on your device (and in your iCloud, if sync is on), including its cost and the text sent and received, so you can review your usage. It keeps the newest 200 records: each time the app starts, older ones are deleted, except a pursuit's latest successful result of each kind and those a meeting plan or debrief was made from. Monthly cost totals are kept. When you delete a meeting, pursuit or company, the text of the requests used only for what you deleted is cleared and their cost is kept. A saved review keeps what the AI suggested after its request record is deleted, until you delete the meeting.

## Contacts

You can add one person at a time without giving Upfront access to your contacts: by choosing them from your contacts, sharing a contact card, dragging a card into the app, or pasting one on a Mac. Only that card is read.

Upfront asks for access to your contacts only if you use one of these:

- **Open in Contacts** or **Update from iPhone Contacts** on a person you've linked to a card. Upfront reads only that card.
- **Contact matching** in Settings, off by default. It searches your contacts for each person you add, by email, phone or name, and links a match. If there's no match, it adds a new card to your contacts. If you change a linked person's title, email or phone, it asks before updating their card. **Link Existing People** shows matching cards for people already in Upfront, for you to confirm one at a time, and adds no cards.

Upfront sends nothing to the AI model from your contacts. A name and title you save on a person are sent like any other person's details.

## What the developer receives

Nothing. Upfront has no analytics, no advertising and no tracking, and it doesn't send your data to the developer or to any third party other than Anthropic (for the AI features you use) and Apple (for iCloud sync, if you turn it on).

If you install Upfront through TestFlight, Apple may share crash reports and any feedback you choose to send with the developer, under Apple's TestFlight terms.

## Deleting your data

- Delete individual records in the app. Deletes also apply on your other synced devices when they next sync. If a device that was offline for a long time still shows something you deleted, delete it there too.
- Deleting the app removes the data stored on that device. iOS may keep your API key in the Keychain after the app is deleted, so remove it first in Settings with Remove Key.
- To remove synced data from iCloud, turn sync off in Upfront's Settings, iCloud Sync, and use Delete iCloud Copy. You can also use your device's iCloud settings to manage Upfront's stored data.
- AI requests already sent to Anthropic are governed by Anthropic's terms for the account that owns the API key.

## Children

Upfront is a business tool and isn't directed at children.

## Changes

If this policy changes, the updated version will be posted at this address with a new effective date.

## Contact

Questions about this policy: app_feedback@hargrove-epc.com
