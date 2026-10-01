---
permalink: /account-deletion/
title: Account Deletion
---

# Account Deletion

StudyCanvas users can permanently delete their account inside the app:

**Settings → Account → Delete Account**

The app displays a deletion warning and requires the user to type **DELETE** before the request can be submitted.

## What is deleted
The production deletion flow removes:

- the active Supabase authentication account,
- user-owned StudyCanvas database records associated with that account,
- private uploaded files stored under that user's StudyCanvas storage path, and
- the local StudyCanvas class cache for that account on the device completing deletion.

Database records owned by the account use deletion cascades so classes, questions, notes, drawings, annotations, flashcards, review progress, exams, AI feedback, and related StudyCanvas records are removed with the account.

## Subscriptions are separate
Deleting a StudyCanvas account does **not** automatically cancel an Apple App Store subscription.

Before or after account deletion, users can open:

**Settings → StudyCanvas Pro → Manage Subscription**

to review or cancel Apple billing.

Apple and RevenueCat may retain transaction or subscription records under their own policies and applicable obligations.

## Provider retention
Infrastructure providers may retain limited logs, backups, security records, or other information for limited periods according to their own retention policies or where reasonably necessary for legal, security, fraud-prevention, accounting, or dispute purposes.

Questions: **coolhandlukere@gmail.com**
