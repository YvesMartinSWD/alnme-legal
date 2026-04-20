---
layout: default
title: Privacy Policy — AL n Me
---

# Privacy Policy — AL n Me

_Last updated: April 20, 2026_

---

## Summary

AL n Me does not collect, transmit, or sell your personal data.
Everything you create in the app stays on your device and in your own iCloud account.
We have no server. We have no account system. We never see your data.

---

## What data the app stores

All data you enter (tasks, events, shopping lists, travel, packing lists, contacts, locations)
is stored exclusively in the app's local Core Data database on your device.

---

## iCloud

**iCloud Backup (optional)**
If you use the backup feature, your data is saved to your personal iCloud account
(`iCloud.com.smartinnovationforyou.Profile`). This is your own private iCloud storage —
Smart Innovation For You has no access to it. You control it through your Apple ID settings.

**iCloud Key-Value Store**
The app stores one piece of data in iCloud KV: the date of your first app launch, used
to manage your 90-day free trial across your devices. This is a single timestamp. It is
stored in your own iCloud account and is not accessible to us.

---

## Subscriptions and payments

All subscription and payment processing is handled exclusively by Apple via StoreKit.
We never receive, store, or process your payment information. We only receive a boolean
entitlement status (subscribed / not subscribed) from Apple's servers.

---

## Crash diagnostics

The app uses two crash diagnostics mechanisms:

**Apple MetricKit**
AL n Me uses Apple's MetricKit framework to receive crash reports. MetricKit delivers
diagnostic data only when you have enabled "Share with App Developers" in your iOS
Settings → Privacy & Security → Analytics & Improvements. We have no control over this
setting — it is entirely your choice. MetricKit reports are stored locally on your device.

**Sentry (crash reporting)**
AL n Me uses Sentry, hosted in the European Union (Frankfurt, Germany), to receive
real-time crash reports. Sentry collects:

- An anonymous random identifier (UUID) — this is **not** your name, email, Apple ID, or
  any identifier that can identify you as a person
- The type, location, and stack trace of the crash
- Your iOS version and device model

Sentry does **not** collect: screenshots, personal data, contacts, location, or any content
you have entered in the app. The data is stored on EU servers (AWS eu-central-1) and is
subject to GDPR. You can read Sentry's privacy policy at [sentry.io/privacy](https://sentry.io/privacy/).

---

## Device permissions

The app requests the following permissions, all used locally on your device only:

| Permission | Why | Data leaves device? |
|---|---|---|
| Location (When In Use) | Show nearby shops on map, geofence notifications | Never |
| Location (Always) | Geofence alerts when app is in background | Never — on-device only |
| Microphone | Voice commands (shopping, tasks, packing) | Never — processed on-device |
| Speech Recognition | Convert voice to text for commands | Apple's on-device engine only |
| Camera | Photos for your profile and shopping items | Never |
| Photo Library | Choose photos from your library | Never |
| Contacts | Import your own contact info at setup | Stored locally, never transmitted |
| Face ID / Touch ID | Encrypt your backup files | Never |
| Notifications | Reminders for tasks, events, geofence alerts | Never |

---

## Third parties

| Service | Purpose | Data sent | Location |
|---|---|---|---|
| Apple iCloud | Backup + trial date sync | Your own data, in your own account | Your Apple ID |
| Apple StoreKit | Subscription processing | Payment handled by Apple only | Apple servers |
| Apple MetricKit | Crash diagnostics (opt-in) | Crash data, on-device | Apple servers |
| Sentry | Real-time crash reports | Anonymous UUID + crash stack | EU (Frankfurt) |

We use no advertising SDKs, no analytics SDKs, and no tracking frameworks.

---

## Children

AL n Me does not knowingly collect data from children under 13.

---

## Your rights (GDPR)

Since we store no personal data on our servers, there is nothing for us to provide,
correct, or delete on our end. All your data is on your device — you can delete it
at any time by deleting the app. iCloud backups can be deleted from your iCloud settings.

For Sentry data: the only identifier is an anonymous UUID. It cannot be linked to you
as a person. If you wish to opt out of crash reporting entirely, contact us and we will
provide a build with Sentry disabled.

---

## Changes to this policy

If this policy changes materially, we will update the "Last updated" date at the top
and note the changes in the App Store release notes.

---

## Contact

Smart Innovation For You
support@smartinnovationforyou.com

---

_This policy applies to AL n Me (com.smartinnovationforyou.ALnMe) on iOS._
