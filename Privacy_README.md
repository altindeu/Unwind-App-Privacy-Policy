# Unwind Privacy Policy

Last updated: July 9, 2026

This privacy policy describes how Unwind handles information in the current app and API codebase. It is written to be understandable to users and maintainers, but it should still be reviewed by legal counsel before publication.

## Summary

Unwind is designed as a supportive AI reflection companion. Most saved reflection data is stored locally on your device. Chat messages and Live Reflection transcripts are sent to Unwind's AI service so the app can generate AI replies. Unwind does not currently offer accounts, cloud backup, export, advertising, third-party analytics, or social features.

Unwind is not a medical professional, therapist, emergency service, or replacement for professional care. If you are in immediate danger or may hurt yourself or someone else, call emergency services now. In the U.S., call or text 988 for the Suicide & Crisis Lifeline.

## Age Requirement

Unwind is intended for people who are at least 13 years old. During onboarding, users confirm that they are 13 or older and understand that Unwind is not emergency or professional care.

## Information Unwind Handles

### Onboarding and Profile Preferences

Unwind stores onboarding and profile preferences on your device, including:

- Display name
- Primary support goal, such as anxiety support, overwhelm, sleep wind-down, self-understanding, or consistency
- Preferred support style
- Initial mood check-in
- Reminder preference
- Voice pace, language, and sound feedback settings

These preferences are used to personalize the app experience. They are not uploaded to an Unwind account because the current app does not have accounts or cloud backup. Some locally generated prompts or context may become part of a chat if you choose to continue that chat.

### Mood Check-Ins, Journal Entries, and Emotional Memory

Unwind stores mood check-ins, daily journal entries, saved emotional memory, local streaks, home path suggestions, and resumable session previews on your device.

This can include:

- Mood labels you choose
- Journal text you write
- Locally generated summaries, themes, excerpts, and suggested next steps
- Dates and timestamps for check-ins, journal entries, saved memories, and streaks

Journal entries and emotional memory are used for local continuity inside the app. They are not directly uploaded just because they are saved. If you later include the same information in a chat or voice reflection, or continue a chat that uses locally generated starter context, that text may be sent to the AI service as described below.

### Chat Text

When you use chat, Unwind sends recent chat messages to Unwind's AI proxy so the app can generate a reply. The proxy forwards the request to OpenAI. The app also saves recent chat sessions locally on your device so you can resume them.

Current code keeps up to 12 saved chat sessions locally. The API proxy trims message history and content before forwarding requests. The current proxy code does not intentionally store chat request bodies or AI responses in a database.

### Live Reflection Voice and Transcripts

When you use Live Reflection, Unwind asks for microphone and speech recognition permission. Your device and platform speech services are used to turn speech into text. Unwind uses the resulting transcript to request an AI reflection through Unwind's AI proxy and OpenAI.

Unwind does not intentionally save raw audio recordings in the current app code. It may save the transcript, AI reflection, and a local memory summary or excerpt on your device for continuity.

### Purchases and Subscriptions

Unwind uses RevenueCat and the App Store or Google Play to offer and manage subscriptions. Purchase processing is handled by those providers, not directly by Unwind.

Unwind may store subscription-related status locally, including:

- Plan type
- Product identifier
- Active entitlement identifier
- Expiration or trial dates
- Renewal status
- Subscription management URL
- Local monthly reflection usage counters

Deleting local app data does not delete purchase records held by Apple, Google, RevenueCat, or payment providers.

### Technical and Operational Data

The AI proxy uses technical information needed to operate the service, including request metadata such as IP address for rate limiting. The current proxy stores rate limit counters in memory and does not intentionally persist prompt or response content.

Hosting providers, OpenAI, RevenueCat, Apple, Google, and device operating systems may process technical logs or service data according to their own policies and agreements.

### Support Communications

If you contact support, Unwind may receive whatever information you choose to send, such as your email address, message text, screenshots, device details, or subscription context. Support requests are used to respond to you and troubleshoot issues.

## How Information Is Used

Unwind uses information to:

- Provide chat and AI reflection features
- Personalize prompts, local summaries, and the home experience
- Save local journal, mood, memory, and preference data
- Check subscription access and monthly reflection limits
- Maintain safety messaging and crisis disclaimers
- Prevent abuse of the AI proxy through rate limiting
- Respond to support requests
- Improve reliability and debug issues during development

Unwind does not currently use personal information for third-party advertising or cross-app tracking.

## Third-Party Services

Unwind currently depends on these categories of third-party services:

- OpenAI: Generates AI chat and reflection responses from text sent through Unwind's proxy.
- RevenueCat: Provides subscription entitlement and product information.
- Apple App Store and Google Play: Process purchases, subscriptions, restores, and subscription management.
- Apple, Google, or device speech services: May process speech recognition when Live Reflection is used, depending on platform and device behavior.
- Hosting provider for the AI proxy: Runs the Unwind API service in production.
- External support and crisis links: Opening email, phone, SMS, browser, or 988 resources leaves the app and is handled by the selected external service.

Unwind does not currently include third-party analytics SDKs, advertising SDKs, crash reporting SDKs, location tracking, contact access, camera access, or health data integrations in the reviewed app code.

## Permissions

Unwind may request:

- Microphone access: To capture speech during Live Reflection.
- Speech recognition access: To convert speech into transcript text for Live Reflection.
- Billing access: To support in-app purchases and subscriptions.

The iOS app configuration also includes photo library permission text for a possible user-selected image flow, but no active photo upload or image selection feature was found in the current reviewed app code. If an image feature is added later, this policy and store disclosures should be updated before release.

You can manage device permissions in your operating system settings.

## Local Storage and Retention

Most saved Unwind data is stored in the app's local device storage. It remains on the device until you delete it in the app, uninstall the app, clear the app's data, or the app overwrites older records according to local limits.

Current local limits include:

- Chat sessions: Up to 12 saved sessions
- Emotional memory entries: Up to 40 saved entries
- Mood check-ins: Up to 40 saved check-ins
- Daily journal entries: Saved by day until deleted through local data deletion or app removal

Local data is protected by the security controls of your device and operating system. Unwind local storage should not be treated as a secure medical record system or encrypted vault.

## Data Deletion and Controls

The Profile screen includes local controls to:

- Clear reflection history
- Reset emotional memory
- Delete all local data
- Restart onboarding
- Manage sound and voice preferences
- Restore or manage purchases

"Delete all local data" removes onboarding answers, chat sessions, daily journal entries, mood check-ins, resumable sessions, saved memories, local reflection usage counters, and local preferences from the device.

Local deletion does not remove data already processed by third-party services, purchase records held by Apple, Google, or RevenueCat, or messages you sent through external support channels. To request help with support records or other provider-managed data, contact support.

## AI Processing

AI replies are generated by sending text to Unwind's AI proxy and OpenAI. This can include chat text, recent chat context, Live Reflection transcripts, and related prompt instructions needed to produce a response.

Do not enter information into chat or Live Reflection that you do not want processed by AI services. Do not enter information into the journal that you do not want stored locally on your device. Avoid sharing highly sensitive personal information unless you understand and accept these risks.

## No Emergency Monitoring

Unwind includes crisis-related language and may respond with emergency guidance when certain crisis phrases are detected. However, Unwind is not monitored by clinicians, does not provide emergency response, and cannot contact emergency services for you.

If you are in immediate danger, call emergency services now. In the U.S., call or text 988 for the Suicide & Crisis Lifeline or visit https://988lifeline.org.

## International Processing

Depending on where you are located and where Unwind's providers operate, information sent to AI, billing, support, hosting, app store, or speech recognition services may be processed in countries other than your own.

## Changes to This Policy

This policy should be updated when Unwind changes its data practices, adds new providers, adds accounts or cloud storage, enables analytics, changes AI processing, introduces image upload, changes subscription handling, or changes user deletion controls.
