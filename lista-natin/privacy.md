---
layout: default
title: ListaNatin Privacy Policy
description: What ListaNatin collects, why, who else can see it, and your rights.
permalink: /lista-natin/privacy/
updated: September 15, 2026
---

## 1. Who We Are, and What This Covers

This Privacy Policy explains what information ListaNatin collects when you use the Service, why we collect it, who else can see it, and what choices you have about it. It's a companion to our App Terms, and it uses the same capitalized words in the same way — a User, a Session Admin, a Session Participant, a Contribution, a Payout Record. If a word here isn't defined, the App Terms' definitions apply.

The Service is provided by Earth Jan Baquir Marzan, registered at 1146 Tramo St., Brgy. Pulang Lupa Uno, Las Piñas City, Metro Manila, 1742. You can reach us at earth.baquir.marzan@gmail.com with any question about this policy or about your own information.

As a reminder from the App Terms: the Service records paluwagan arrangements. It does not hold, receive, transmit, escrow, or guarantee funds, and it has no payment integration of any kind. Because money never touches the Service, this Privacy Policy never has to explain how we protect a card number, a bank account, or any other payment credential — we hold none, because we never had one to begin with.

## 2. What We Collect — and What We Don't

We collect only what the Service needs to run a paluwagan and to reach you. Here's the actual list.

**What we collect:**

- **Your name.** Your User record carries a name, and it stays the same once it's there, so the other members of your paluwagans can trust who they're dealing with.
- **A profile photo.** Your User record also carries a link to a profile photo, shown next to your name in the app.
- **Your mobile number, and whether it's been verified** — only if you choose to add one. Verification happens by SMS code, sent through Firebase's phone-verification system. Once a number is verified, we keep it and its verified status in a separate, locked-down record — no one can read or write it directly, not even you from inside the app; only three of our own server functions can touch it: one to verify a new number, one that lets another member of your paluwagan look up how to reach you (Section 4 explains exactly when that's allowed), and one to clear it if you delete your account. We also keep a separate server-side list of claimed numbers, holding the number, the id of the User who claimed it, and when it was created and last changed — that's how the same verified number can't end up attached to two different Users at once. Your User record stores the id of that claim.
- **A push-notification token and your notification preference** — so we can send you alerts about due dates, approvals, and payouts, and so you can turn that off whenever you like.
- **The notifications we've sent you.** Each one is stored against your User's id with its title, its message, what kind of notification it is, which Session it belongs to, and whether you've read it — that's how the app can show you a list you've already seen and mark it read.
- **Your paluwagan activity** — the Sessions you belong to or run, your role in each one, your Contributions (a hulog), your Payout Records (sahod), notes you or others write on a Contribution or on an approval or rejection, invites you send or receive, and a permanent activity log of what happened in each Session.
- **A problem report, if you send us one.** Tapping "Report a problem" writes a record directly into our own database — the category you picked, whatever you typed in the note field, your app version, and, if you attached one, a photo. We may also collect basic device information: platform, operating system version, and device model. The report is tied to your User's id, so it isn't anonymous to us, though Section 6 explains what happens to that link if you later delete your account. This is kept deliberately light: not detailed activity logs, not behavioral tracking.
- **A report or a block, if you're involved in one.** If another member reports something you posted or reports you directly, we keep a record of it — who filed it, what category it falls under, and, for a report about specific content, a copy of that content as it stood when it was reported. A photo attached to a report is stored the same way a problem-report photo is. If you block another member, or another member blocks you, we keep a record of that too. Section 4 explains who can see any of this — and it isn't the person being reported or blocked.

**What we don't collect:**

- **No Contribution proof photos, at least not yet.** The Service lets you attach a photo as proof of a Contribution — for example, a screenshot of a GCash confirmation — but as of this writing, that photo never leaves your device to our servers. What gets saved is a placeholder marker noting that you attempted to attach one, not the image itself. If this changes, we'll update this policy before it does. A photo attached to a problem report or a safety report is different — see above — those really are uploaded and stored.
- **No email address in our own database.** ListaNatin's own records never store your email address. If you sign in with Facebook and grant it the email permission, that address may exist inside Firebase Authentication's own managed record of your sign-in — a system operated by Google, separate from our database — but our app never reads or writes it as a stored field.
- **No card numbers, bank details, or payment credentials of any kind.** As explained in Section 1, the Service never touches money, so there's nothing of that kind for us to hold.
- **No behavioral tracking, no analytics, and no advertising events.** We don't watch how you use the app beyond what's needed to run it. One related detail, disclosed rather than buried: the iOS build configuration contains SKAdNetwork entries — Apple's ad-attribution framework — added automatically by the Facebook login SDK's setup. The app itself sends no ad events, and we use Facebook for sign-in only.
- **No crash-reporting tool is active yet — but here's exactly what it will do once it is.** We've built an error-monitoring tool called Sentry into the app, to help us catch and fix crashes and bugs, but it's switched off by default in every environment today, and no released build of the app has ever run it — as of this writing, it watches nobody. When it's switched on for a released build, this is what it sends: a stack trace and basic device/operating-system information when the app hits an error, plus a lightweight signal each time the app starts or goes to the background (so we can tell how often the app runs into trouble, not what you do inside it) — no performance tracing, and no session replay. Each report is tagged with your User's id, so we can tell how many different people hit the same issue; it is not anonymous. Before anything leaves your device, we strip out your mobile number, your name and the names of anyone else involved, any note you've written, and any photo or image reference, so none of that reaches the tool even while it's active — and it never sees the network traffic for verifying a mobile number, looking up a member's contact, or deleting an account.
- **No location, and no device model or operating system version stored on our servers, outside of a problem report or the crash-monitoring tool described just above.** Your app version is read on your own device to show on your Profile screen.

## 3. Why We Collect It

We keep a name and a profile photo on your User so the Service can show, correctly and consistently, who's who in every paluwagan you're part of — the same identity across every Session, so nobody can be confused for someone else.

We keep your mobile number, if you add one, so you have a verified way to be reached and recognized, separate from your sign-in provider. The separate list of claimed numbers exists so the same verified number can't end up attached to two different Users at once — a check that has to happen on the server rather than on any one device.

We keep your push-notification token, and honor your notification preference, so we can tell you when a Contribution is due, when one of yours is approved or rejected, or when a Payout Record is created — and so you can stop those alerts at any time. We keep the notifications themselves so you can open the app later and read what you missed.

We keep your Contributions, Payout Records, notes, invites, and activity log because recording that information accurately is the entire purpose of the Service. Without it, there's no shared record to eliminate the Messenger back-and-forth a paluwagan usually runs on.

If you send us a problem report, we keep it — the category, your note, your app version, basic device information, and any photo you attached — so we can actually look into and fix what you're telling us about. We keep a record of any report or block involving you, filed by you or about you, because a paluwagan only works if members can flag bad behavior and protect themselves from it, and because our ability to offer both is a condition of publishing this app at all. Section 4 explains who can see these records; it's a narrow list, and never the person being reported or blocked.

## 4. Who Else Can See It

**Other members of your paluwagan.** Within a Session, the Session Admin and the Session Participants of that same Session can see what the Service shows about each other — names, profile photos, Contributions, Payout Records, and any notes attached to them. This is by design: a paluwagan only works as a shared record if the people in it can see the same thing. Put plainly: what you enter in a paluwagan is visible to the other members of that paluwagan — with one deliberate exception, your mobile number. That's visible only in one direction, checked by our own servers each time you or another member asks: a Session Admin can look up an active Session Participant's number, and a Session Participant can look up their own Session's Admin's number, but never another participant's, and never yours at all if you've blocked (or been blocked by) the person asking. Getting to any of it takes a signed-in User — the Service requires you to sign in before it will show you anything — your device talks to our database over encrypted connections, and all of it sits on Google's managed infrastructure rather than on servers we run ourselves.

**Reports and blocks.** If you report content or another member, or block someone, that record is visible only to us — reviewed directly in our own systems — never to the person you reported or blocked, and never surfaced back to you either. The App Terms explain what reporting and blocking actually do inside a Session; this is only about who can see the record of it.

**Problem reports.** The same is true of a problem report you send us: it's visible only to us, for troubleshooting. No other member of your paluwagan, and no outside party, ever sees it.

**The outside services that help us run the Service.** We rely on a small number of external providers, and each of them sees only what its role requires:

- **Google/Firebase** — our database, our authentication system, and our background jobs all run on Firebase, a Google product. This is where your name, photo, paluwagan data, notifications, and push token are actually stored, where your phone number is sent to deliver an SMS verification code, and — locked down separately, as Section 2 explains — where your mobile number itself lives. Some of those background jobs run on a schedule — sending due reminders and late alerts, recording payout releases, and closing grace periods. Others run on demand, triggered by something you or another member does: verifying a mobile number, looking up a member's contact, deleting an account, submitting a Contribution, resolving an approval or rejection, and marking notifications as read, among others.
- **Expo's push notification service** (exp.host) — receives your push token and the content of a notification (its title, message, and related data) whenever we send you one, so it can be delivered to your device.
- **Facebook (Meta)** — receives your login request if you sign in with Facebook, and returns your basic profile information to Firebase Authentication as part of that sign-in. We use Facebook for login only — no analytics or advertising events are sent to or from Facebook by the Service.
- **Sentry** — only once we switch on the error-monitoring tool described in Section 2, and only for a released build. It's off today. When active, it receives exactly what Section 2 describes: crash reports and lightweight app-start/background signals, with your identifying details stripped out first.

We don't sell your information to anyone, and we don't share it with any advertiser or data broker. No other outside service receives your data.

## 5. Where It's Stored, and How It's Protected

Your information is stored in Cloud Firestore and Firebase Authentication, both Google Cloud services, and is handled by background jobs that also run on Google's Cloud Functions. ListaNatin doesn't run its own servers for any of this. Because Google operates that infrastructure across many regions, your information may be stored or processed on servers outside the Philippines.

We do use Firebase Storage — a separate Google Cloud service — to hold a photo you attach to a problem report or a safety report. A Contribution proof photo is the one exception: as Section 2 explains, that one still never leaves your device.

On protection, we'd rather be modest and accurate than impressive. Connections between your device and Google's services are encrypted in transit. The Service requires you to sign in before it will show you anything. Your mobile number is locked down at the database level and reachable only through our own server functions — no client, including your own, can read or write it directly. Verified mobile numbers are recorded by a server function rather than written directly from a phone, so the "verified" mark means what it says. We hold no security certification and won't claim one. If you think something has gone wrong with your information, write to us and we'll look into it.

## 6. How Long We Keep It, and What Deletion Actually Does

Most of what the Service records is meant to last. Your Contributions and each Session's activity log are permanent, append-only records — once written, nobody, including you, can edit or delete them, because other members' own records depend on that history staying complete. Consistent with that, we never hard-delete a User: your identity doesn't disappear from the paluwagans you've been part of just because you stop using the app. Section 7 explains the legal basis for keeping that shared history and how it fits with your right to erasure.

Some things stay even after your User is deleted, and for different reasons than your paluwagan history. If you've sent us a problem report, the report itself stays in our records for troubleshooting, but we remove the link to your identity, so it's no longer connected to you. Your stored notifications also stay — they're just delivery records, not part of anyone's financial history, but nothing about deletion clears them today. And if a report or a block involving you exists — one you filed, one filed about you, or a block between you and another member — that record stays too, because a reporter's ability to stay anonymous, and a block's ability to keep working, both depend on the record surviving even after one side's account is gone.

You can ask us to deactivate or delete your ListaNatin User, as long as you don't have an Active Obligation outstanding — for example, a cycle that's due with no approved Contribution from you yet. This protects the other members of your paluwagan, whose records depend on yours being complete. You can do this from inside the app, from your Profile screen, or from the web request page at https://tanoru-hq.github.io/lista-natin/delete-account/ — both go through the same process, described here.

Deleting your User clears a specific list, spread across two places. On your own User record: your profile photo, your push-notification token, your notification preference, and any sign-in providers linked to it. On the separate, locked-down record described in Section 2: your mobile number and whether it was verified. Your claim on that verified number is also released — the entry in the separate claimed-numbers list is deleted outright, which frees the number to be verified again by someone else, or by you on a new User. Your name and your history — your Contributions, Payout Records, and activity log entries — are kept, because erasing them would leave gaps in other people's records that don't belong only to you. Deleting your User doesn't block you from signing back in; you'll be recognized as the same User if you do.

## 7. Your Choices and Rights

Inside the app, you can turn push notifications off at any time, add or remove your mobile number, and review the Terms and Conditions your Session Admin wrote for any paluwagan you belong to. You can also request deletion of your User, subject to the Active Obligation limit described in Section 6.

Philippine law expects us to say plainly on what basis we handle your information. Three bases apply. First, running the arrangement you joined: we can't record a paluwagan for you without recording who you are, what you contributed, and what you're due. Second, your own consent, for the parts that are yours to switch on and off — adding and verifying a mobile number, and turning push notifications on. Third, the legitimate interests of the other members of your paluwagans, whose own financial records name you and depend on yours.

Because ListaNatin operates in the Philippines, your information is also protected under the Data Privacy Act of 2012 (Republic Act No. 10173). That law gives you the right to know what information we hold about you, to have it corrected if it's wrong, to object to certain uses of it, to have it erased or blocked in appropriate cases, to be compensated for damages caused by a violation of the Act, to receive a copy of your information in a portable format, and to file a complaint with the National Privacy Commission if you believe your rights have been violated. To exercise any of these, write to us at earth.baquir.marzan@gmail.com.

The right to erasure deserves a straight answer rather than a comfortable one, because it sits against the permanence described in Section 6. Where the law requires us to erase or block your information, we will. But a paluwagan record is not yours alone: every Contribution you made is also part of the record of the Session Admin who approved it and of the Session Participants whose payout order depends on it. Removing your entries would corrupt financial history that belongs to other people as much as to you. So we keep shared paluwagan history on the basis of those members' legitimate interests and the integrity of a shared ledger, and we clear the personal details listed in Section 6 that aren't part of that shared record. If you think that balance is wrong in your case, write to us and say so.

## 8. Children

You must be at least 13 years old to use the Service — the same minimum age set by our sign-in provider. We don't knowingly collect information from anyone younger than that, and if we learn that we have, we'll delete it.

## 9. Changes to This Policy

We may update this Privacy Policy from time to time — to reflect a change to the Service, to comply with the law, or to describe something more clearly. The version published at this address is always the current one. If a change is significant, we'll make reasonable efforts to let you know inside the app.

Last updated: September 15, 2026.

## 10. Contact

If you have a question about this Privacy Policy, or about the information we hold about you, write to Earth Jan Baquir Marzan at earth.baquir.marzan@gmail.com, or by mail at 1146 Tramo St., Brgy. Pulang Lupa Uno, Las Piñas City, Metro Manila, 1742.
