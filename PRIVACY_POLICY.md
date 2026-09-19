# Privacy Policy for Vulcan

**Last Updated:** September 19, 2026
**Effective Date:** January 4, 2026

---

## Introduction

Vulcan ("we", "our", or "us") is operated by **Paul Vosloo** and provides a mobile application (the "App") for tracking custom motorcycle build projects. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our App.

By using Vulcan, you agree to the collection and use of information in accordance with this policy.

---

## Information We Collect

### 1. Information You Provide Directly

**Build Data**
- Project names, descriptions, and notes
- Build phases and progress information
- Start dates, deadlines, and timestamps
- Task lists and completion status

**Photos and Media**
- Build progress photos you upload or capture
- Cover photos for builds
- Document scans and uploads
- These stay local to your device **unless** you include them in a
  published customer portal (see below), in which case a copy is
  uploaded to our backend provider, Supabase

**Customer Information** (that you enter for your customers)
- Customer names, phone numbers, email addresses
- If you publish a customer portal for Solo Builder/Pro Shop's customer
  sharing feature, the customer's name and whichever of your build's
  progress, photos, cost total, and deadline you've chosen to make
  visible are uploaded to Supabase so the portal link works for someone
  without the app. This is a **point-in-time snapshot**, not continuous
  syncing — it updates only when you publish again

**Account Information** (Solo Builder, Pro Shop, and builder directory)
- Email address and password, or your Apple ID identifier if you use
  Sign in with Apple
- Required to subscribe, or to browse or publish to the builder
  directory — not required to track your own build on the Free plan
- Handled by Supabase Auth (see Third-Party Services below)

**Builder Directory Profile** (if you publish one, Pro Shop only)
- Business name, bio, photos, location, and contact details you choose
  to submit — stored on Supabase and publicly visible to other Vulcan
  users once published

**Voice Recordings** (Temporary - Not Stored)
- Audio recordings when you use voice input features
- These are sent to Groq's Whisper API for transcription only
- Audio files are **immediately deleted** after transcription completes
- We do **NOT** store voice recordings on our servers or your device

**Cost and Financial Data**
- Parts costs and descriptions
- Labour hours and rates
- Invoice data — invoices you generate stay on your device and in
  whatever app (Mail, Files, etc.) you choose to send or save them
  through; we never see or store them
- Itemized cost data always stays local. If you publish a customer
  portal with "Cost Total" visibility turned on, only the **total**
  figure (not the itemized breakdown) is uploaded to Supabase

### 2. Automatically Collected Information

**Device Information**
- Device type and model
- Operating system version (iOS)
- App version
- Device language settings

**Usage Data**
- App features you use
- Screens visited
- Anonymous crash reports
- Performance metrics

**Subscription Information**
- Subscription tier (Free/Solo Builder/Pro Shop)
- Purchase history through Apple App Store
- Subscription status and renewal dates
- Managed through RevenueCat (see Third-Party Services below)

---

## How We Use Your Information

We use the collected information for:

### 1. App Functionality
- Store and display your build data locally on your device
- Process voice input through Groq's Whisper API for transcription
- Manage your subscription status through RevenueCat
- Authenticate your account through Supabase, for Solo Builder/Pro Shop
  and the builder directory
- Host published customer portals and builder directory listings
  through Supabase
- Calculate cost totals and summaries

### 2. App Improvement
- Analyze anonymous usage patterns
- Identify and fix bugs and crashes
- Improve features based on how they're used
- Optimize app performance

### 3. Customer Support
- Respond to your support requests
- Troubleshoot technical issues
- Communicate important updates

### 4. Legal Compliance
- Comply with applicable laws and regulations
- Enforce our Terms of Service
- Protect our rights and the rights of our users

---

## Data Storage and Security

### Local Storage
**IMPORTANT:** All your build data is stored **locally on your device only** using encrypted AsyncStorage.

- We do **NOT** automatically back up your data to cloud servers
- We do **NOT** have access to your build data, photos, or customer
  information, **except** for what you explicitly publish via a
  customer portal or a builder directory listing (see below) — that
  data is stored on our backend provider, Supabase, so it can be viewed
  by people without the app
- **You are responsible** for backing up your device to prevent data loss

### Data Security Measures
- Encrypted local storage using iOS secure storage mechanisms
- HTTPS encryption for all API communications (voice transcription, subscriptions, account sync)
- No server-side storage of your build data, photos, or customer
  information beyond what you've chosen to publish

### Third-Party Security
- **Groq:** Voice recordings transmitted over encrypted HTTPS connections, immediately deleted after transcription
- **RevenueCat:** Payment and subscription data encrypted and PCI-DSS compliant
- **Supabase:** Account, published portal, and published builder profile data encrypted in transit (HTTPS) and at rest

---

## Third-Party Services

We use the following third-party services that may collect and process data:

### 1. Groq (Whisper API)
- **Purpose:** Voice-to-text transcription
- **Data Shared:** Temporary audio recordings when you use voice input
- **Privacy Policy:** https://groq.com/privacy-policy/
- **Data Retention:** Audio files are immediately deleted after transcription - Groq does not store them
- **How to Opt-Out:** Don't use the voice input feature (you can still manually type)

### 2. RevenueCat
- **Purpose:** Subscription and in-app purchase management
- **Data Shared:** Subscription status, purchase history, Apple App Store receipt data, anonymous device identifiers
- **Privacy Policy:** https://www.revenuecat.com/privacy
- **Data Retention:** Per RevenueCat's privacy policy
- **Usage:** Validates your subscription status and manages entitlements

### 3. Apple App Store
- **Purpose:** App distribution, in-app purchases, analytics, crash reports
- **Data Shared:** Anonymous usage data, crash logs, subscription purchases
- **Privacy Policy:** https://www.apple.com/legal/privacy
- **Data Retention:** Per Apple's privacy policy

### 4. Supabase
- **Purpose:** Account authentication (Solo Builder, Pro Shop, and the
  builder directory), and hosting for customer portals and builder
  directory listings you choose to publish
- **Data Shared:** Email address or Apple ID identifier; if you publish
  them, customer portal snapshot data (customer name, and whichever of
  progress/photos/cost total/deadline you've made visible) and/or
  builder directory profile data
- **Privacy Policy:** https://supabase.com/privacy
- **Data Retention:** Until you delete the published item or your
  account, or contact us to request deletion
- **How to Opt-Out:** Don't create an account — this only affects
  Solo Builder/Pro Shop features and the builder directory; tracking
  your own build never requires one

---

## Data Sharing and Disclosure

**We do NOT sell your personal information to third parties.**

We share data only in these limited circumstances:

### 1. With Your Explicit Consent
When you choose to publish a customer portal or a builder directory
listing, the data covered by that feature (see **Third-Party
Services → Supabase** above) becomes visible to whoever you share the
link with, or to other Vulcan users browsing the directory. This is
the main way information leaves your device, and it only happens when
you take that action.

### 2. Service Providers
- **Groq:** Only for voice transcription (audio immediately deleted)
- **RevenueCat:** Only for subscription management
- **Apple:** Only for app functionality and analytics (anonymous)
- **Supabase:** Account authentication, and hosting whatever you've
  chosen to publish (customer portals, builder directory listings)

### 3. Legal Requirements
We may disclose information if required by law, court order, or government regulation, or to:
- Protect our legal rights
- Prevent fraud or illegal activity
- Protect the safety of our users or the public

### 4. Business Transfer
If we merge with or are acquired by another company, user data may be transferred as part of that transaction. You'll be notified via email and/or in-app notice.

**We do NOT share, unless you explicitly publish it as described above:**
- Your build data with anyone
- Photos you upload with any third parties
- Customer information you enter
- Cost or financial data
- Any personally identifiable information for marketing purposes

---

## Your Rights and Choices

You have the following rights regarding your data:

### Data Access
- View all your data within the app at any time
- Request a data export by contacting **paul@builtbyomnia.com**

### Data Deletion
You can delete your data at any time:
- Delete individual builds within the app (deletes all associated photos, tasks, costs)
- Delete photos from build timelines
- Remove a published customer portal link from within the app (Portal
  tab → Remove Portal Link) — it stops working immediately
- Unpublish a builder directory listing from within the app
- Uninstall the app to remove **all local data** from your device
- To delete your account (email/password or Sign in with Apple) and any
  data associated with it on Supabase, contact
  **paul@builtbyomnia.com**

**Note:** Because build data is stored locally, uninstalling the app permanently deletes it. Make sure to back up anything important before uninstalling. Account data and anything you've published (portals, builder listings) live on our servers and aren't affected by uninstalling — remove them from within the app, or contact us, before uninstalling if you want them gone too.

### Opt-Out Options
- **Voice Input:** Simply don't use the microphone button - all features work with manual text input
- **Analytics:** We collect minimal anonymous analytics; currently cannot be disabled
- **Subscription Data:** Required for subscription features to work
- **Account/Publishing:** Don't create an account — tracking your own build never requires one

### Data Portability
- Contact **paul@builtbyomnia.com** to request a copy of your data
- We'll provide your data in JSON format within 30 days
- You can then import this data elsewhere

---

## Children's Privacy

Vulcan is **not intended for users under 13 years of age**.

We do not knowingly collect personal information from children under 13. If we discover we have collected data from a child under 13, we will delete it immediately.

If you believe we have collected information from a child under 13, please contact us at **paul@builtbyomnia.com**.

---

## International Users

Vulcan is available worldwide via the Apple App Store.

### Data Processing
- **Build data:** Processed and stored locally on your device (wherever you are)
- **Voice transcription:** Processed by Groq's servers (US-based)
- **Subscription data:** Processed by RevenueCat (US-based) and Apple (worldwide)
- **Account, published portal, and published builder profile data:**
  Processed and stored by Supabase, in the data center region selected
  for our project *(update this line with the actual region if you want
  it stated explicitly — check your Supabase project settings)*

### European Users (GDPR)
If you're in the European Economic Area (EEA), you have additional rights:
- **Right to access** your personal data
- **Right to rectification** (correct inaccurate data)
- **Right to erasure** ("right to be forgotten")
- **Right to restrict processing**
- **Right to data portability**
- **Right to object** to processing
- **Right to withdraw consent** at any time

To exercise these rights, contact **paul@builtbyomnia.com**.

---

## Data Retention

### How Long We Keep Data

**Build Data, Photos, Tasks, Costs:**
- Stored locally on your device until you delete them
- We have no access to this data and cannot delete it remotely
- Deleted when you delete builds or uninstall the app

**Voice Recordings:**
- **NOT stored** - immediately deleted after transcription (typically within 5 seconds)

**Subscription Data:**
- Retained by RevenueCat per their data retention policy
- Retained by Apple per their data retention policy
- Typically retained for the duration of your subscription plus required legal retention periods

**Account Data:**
- Retained until you delete your account (contact **paul@builtbyomnia.com**)

**Published Customer Portals:**
- Remain live at their link with no automatic expiry, until you remove
  them from the app (Portal tab → Remove Portal Link) or contact us

**Published Builder Directory Listings:**
- Remain visible until you unpublish them from within the app or
  contact us

**Crash Reports:**
- Anonymous crash logs retained for 90 days
- Used solely for debugging and app improvement

---

## Your California Privacy Rights (CCPA)

If you're a California resident, you have these rights under the California Consumer Privacy Act (CCPA):

### Right to Know
You can request:
- Categories of personal information we collect
- Purposes for collecting personal information
- Categories of sources from which we collect information
- Categories of third parties with whom we share information

### Right to Delete
Request deletion of your personal information (subject to legal exceptions).

### Right to Opt-Out of Sale
We do **NOT** sell your personal information, so there's nothing to opt out of.

### Right to Non-Discrimination
We will not discriminate against you for exercising your CCPA rights.

**To exercise these rights, contact:** paul@builtbyomnia.com

We'll respond within 45 days.

---

## Data Security

We take reasonable measures to protect your information:

### Technical Measures
- Encrypted local storage (iOS Keychain and secure storage)
- HTTPS/TLS encryption for all network communications
- Secure API authentication with third-party services

### Organizational Measures
- Access to systems restricted to essential personnel only
- Regular security reviews and updates
- Incident response procedures

**However, please note:**
- No method of transmission or storage is 100% secure
- You're responsible for keeping your device secure (passcode, Face ID, etc.)
- We cannot guarantee absolute security

**If you discover a security vulnerability, please report it to:** paul@builtbyomnia.com

---

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect:
- Changes in our data practices
- Changes in applicable laws
- New features or services
- User feedback

### How We'll Notify You
When we make changes:
- Update the "Last Updated" date at the top
- Post the new policy in-app and at our privacy policy URL
- For **material changes**, we'll provide prominent in-app notice or email notification

**Continued use of the app after changes constitutes acceptance** of the updated policy.

---

## Contact Us

If you have questions, concerns, or requests regarding this Privacy Policy or your data:

**Privacy Inquiries:**
Email: **paul@builtbyomnia.com**

**General Support:**
Email: **paul@builtbyomnia.com**

**Mailing Address (Optional - add if you want):**
Paul Vosloo
Built by Omnia
[Your City, Country]

We'll respond to privacy inquiries within **30 days**.

---

## Legal Information

**Service Provider:** Paul Vosloo
**App Name:** Vulcan
**Platform:** iOS (App Store)

This Privacy Policy is governed by the laws of **South Africa** (update this if you're in a different jurisdiction).

---

**Vulcan Privacy Policy v1.1**
**Effective Date:** January 4, 2026
**Last Updated:** September 19, 2026

---

## Summary (TL;DR)

**What we collect:**
- ✓ Build data, photos, tasks (stored **locally on your device only**)
- ✓ Voice recordings (sent to Groq, **immediately deleted**, not stored)
- ✓ Subscription info (managed by RevenueCat and Apple)
- ✓ Account info — email/password or Apple ID identifier (Supabase),
  only if you use Solo Builder, Pro Shop, or the builder directory
- ✓ Whatever you explicitly publish — a customer portal snapshot, or a
  builder directory listing (Supabase)
- ✓ Anonymous usage data (crashes, feature usage)

**What we DON'T do:**
- ✗ Store your data on our servers, unless you explicitly publish it
- ✗ Sell your data to anyone
- ✗ Access your build data or photos beyond what you've published
- ✗ Store voice recordings

**Your data is YOURS:**
- Delete anytime within the app
- Build data stored locally on your device only
- Published portals/listings can be removed from within the app
- Back up your device to prevent loss

**Questions?** Contact paul@builtbyomnia.com
