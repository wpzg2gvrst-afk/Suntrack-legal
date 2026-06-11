# suntrack — privacy policy

**Effective date: 2026-06-10**

This policy explains what data suntrack ("we", "us", "our") collects from you, why, and what you can do about it. We tried to write it like a person, not a lawyer.

If you have questions, email ****[suntrackhelp@gmail.com](mailto:suntrackhelp@gmail.com)****.

---

## 1. What suntrack does

suntrack is an alarm app you can share with your friends. Each friend can pick a song, mood, and short note to attach to your morning alarm, so you wake up to a small gift instead of a generic ring. To make this work, we need to know who you are, who your friends are, and when your alarm should fire.

---

## 2. Data we collect

We only collect what we need. Specifically:

| Data | Why we need it |
|------|----------------|
| Email address | Sign-in + password recovery |
| Display name | Shown to your friends ("mikey sent you a suntrack") |
| @username | How friends find you to add you |
| Password | Stored securely (hashed, never visible to us in plain text) — handled by our auth provider, Supabase |
| Alarms you create (time, repeat days) | So we can schedule them and let friends send you suntracks for them |
| Suntracks you send and receive (mood, song link, short note up to 280 characters) | This is the core feature |
| Your friend connections | So friends can see each other's alarms and send suntracks |
| Your preferred default alarm sound | Optional — plays if no friend sends a suntrack |
| Your preferred music app (Spotify or Apple Music) | Optional — shown to friends so they know which kind of song link to send |
| iOS push notification token | So we can wake up the app silently when a friend sends you a suntrack |

We do **not** collect:

- Your location
- Your contacts
- Microphone, camera, or photo access
- Health data
- Financial data
- Advertising identifiers
- Anything for ad targeting

---

## 3. How we use your data

Everything we collect is used solely to make suntrack work for you. We do not use your data for advertising, profiling, or any purpose unrelated to the app.

---

## 4. Who we share data with

We share the minimum necessary data with these service providers, and only to operate the app:

- **Supabase** — hosts our database, handles user authentication, and runs the edge functions that deliver suntracks between phones. Supabase's privacy policy: https://supabase.com/privacy
- **Apple Push Notification Service (APNs)** — receives a silent ping with your device token whenever a friend sends you a suntrack, so your phone wakes up to sync. The ping does not contain any of your personal data — just a wake-up signal.

When you tap a song link inside a suntrack, you leave suntrack and open **Spotify** or **Apple Music** in their own app or website. Anything you do there is governed by their privacy policies, not ours.

**We do not sell your data to anyone, ever.**

---

## 5. How long we keep your data

We keep your data as long as your account exists. When you delete your account (via the "delete account" button in your profile), we permanently delete:

- Your profile, username, and email
- All alarms you created
- All suntracks you sent and received
- Your friend connections
- Your device token

This deletion is immediate and cannot be undone. Your friends' lists update to remove you; any historical suntrack content you sent them is also deleted.

---

## 6. Your rights

You can:

- **Access** the data we have about you — most of it is shown directly in the app on your profile and alarm screens. For anything else, email us.
- **Correct** your data by editing it in the app.
- **Delete** your account at any time via Profile → "delete account".
- **Ask questions** about how we handle your data — email [suntrackhelp@gmail.com](mailto:suntrackhelp@gmail.com) and we'll respond.

If you're in the EU, UK, or California, you have additional rights under GDPR and CCPA (right to portability, right to object to processing, etc.). Email us to exercise any of them.

---

## 7. Security

Your password is hashed and never stored in readable form. Communication between the app and our servers is encrypted (HTTPS). Push notifications use Apple's encrypted infrastructure.

That said, no system is perfectly secure. If we ever discover a breach affecting your data, we'll notify you within 72 hours via the email on file.

---

## 8. Children

suntrack is not directed at children under 13. We do not knowingly collect data from anyone under 13. If you believe a child has signed up, email us and we'll delete the account.

---

## 9. Changes to this policy

We may update this policy as suntrack evolves. If we make material changes, we'll bump the effective date at the top and notify you the next time you open the app.

---

## 10. Contact

**Email:** [suntrackhelp@gmail.com](mailto:suntrackhelp@gmail.com)

— the suntrack team ☀️🎵
