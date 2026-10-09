# Privacy policy for Reroll

Effective date: 9 October 2026

Reroll is developed by Faruq Batula ("the Service Provider"). This policy explains how Reroll ("the Application") handles your information.

## The short version

Reroll has no accounts, no advertising, and no cross-app tracking. Your lives, your avatar, and your purchases stay on your iPhone, and nothing is ever sold or shared with data brokers. We do not build a profile of you, and nothing that leaves your device can identify you.

A few things may leave your device, each described in full below: the actions you type (on some iPhones), a small batch of anonymous usage counts, and the configuration files the app downloads. None of them include your identity, your contacts, your location, or the content of your lives.

## What is sent when you type an action, and only on some iPhones

Typing your own actions needs an AI storyteller:

- **iPhones with Apple Intelligence** (iPhone 15 Pro and newer, running iOS 26 or later) run the storyteller **entirely on your device**. Nothing is transmitted.
- **iPhones without Apple Intelligence** cannot run it locally. On those devices, each time you submit a typed action we send:
  - **The action text you typed.**
  - **The life context needed to judge it:** your character's age, era, country, occupation, education, money and health band, the first names and roles of people in that life, and active story flags.
  - **A random per-install identifier**, used to count your free actions and apply fair-use limits.

We do **not** send your name, contacts, location, email, device identifiers, your other lives, or your purchase history.

Settings ▸ On this iPhone tells you which applies to your device.

## What is kept

**The action text and life context are not stored.** They are processed to produce the outcome and then discarded. They are never written to a database, never logged, and never used to train any AI model.

**The per-install identifier is kept**, as a salted cryptographic hash, only to count how many free actions an installation has used and, for at most two days, to limit how often one installation can send usage counts. This identifier is a random value created when you install the app. It is **not** your Apple ID, not your advertising identifier (IDFA), not your vendor identifier (IDFV), and not derived from any device or hardware identifier. It cannot be linked to you, to your device, or to anything else about you, and it is never used for advertising, tracking or profiling. Deleting the app forgets it — which also resets your free actions.

Our server also keeps aggregate counters (how many actions have been used, and a running total of processing cost). These contain no text and are not tied to any person.

## Anonymous usage counts

To understand whether new features actually help players — for example, whether the daily challenge or the new levels bring people back — the app may send a small batch of **anonymous numeric counts**: which days you played and roughly how long after installing; how many sessions you played and roughly how many in-game years each one covered (in ranges, not exact numbers); when lives start and end; progress through game levels and ranks, and whether a mini-game was played or left to fate; whether the between-lives game was played, and roughly how far you got (in ranges); whether a reminder notification was offered, allowed or opened; which screen a purchase prompt was shown on, and whether a trial or purchase followed (the kind of product only — never a price or any payment detail). This is sent together with the same random per-install identifier described above.

Each count also carries a **label for which version of the app you are seeing** — for example, the version with levels or the classic version. To compare versions fairly, a new installation may be given one of them at random; installations from before an update keep the version they had, and installations that were already shown the version with levels before the comparison began keep it too. The label is one of a few fixed words, says nothing about you, and is not linked to your identity.

It contains **only numbers, true/false values, and a fixed list of event names**. No life content, no text you type, and no free text of any kind is included — the data is built so that none can be. It is used to understand how features are used, and for nothing else. It is never sold, never shared with data brokers, and never used for advertising or to build a profile of you.

Unlike typed actions, this is not limited to iPhones without Apple Intelligence — it may run on any device where the feature is enabled.

## The configuration files

The app downloads small **public configuration files** over HTTPS to receive game settings: each day's challenge settings (the daily objective, notification timing, and streak rules) and which game features are switched on. These are ordinary file downloads — the same files for every player — and **nothing about you is sent with them**. They contain no identifier, no device information, and no data about your play.

As with any internet request, the service hosting the files (GitHub Pages, a third party) necessarily sees your device's IP address and the time of the request. Nothing else is transmitted, and nothing about you travels outbound.

## What is never collected

Regardless of your device or which features are enabled, Reroll never transmits: your name, contacts, location, or email; any Apple, advertising, or hardware device identifier; your other lives, your saved life content, or your purchase history (beyond the anonymous count, described above, that a trial or purchase happened and the kind of product); and it contains no advertising SDK and no cross-app tracking of any kind.

## Who processes it

Our service runs on Cloudflare Workers, and the writing is performed by an open AI model on Cloudflare Workers AI. Cloudflare does not retain the prompts or outputs sent to Workers AI, and does not use them to train AI models. Anonymous usage counts are totalled on Cloudflare (Workers Analytics Engine) without any identifier and kept for up to three months. The configuration files are hosted on GitHub Pages.

## What stays on your device

Your lives (including the text of actions you have typed, saved so a life can be replayed exactly), your avatar, your subscription status, and the app's own on-device statistics are stored on your iPhone only and are never transmitted. (These are separate from the anonymous usage counts described above.)

## Children

Reroll is not directed at children under 13, and we do not knowingly collect personal information from children.

## Your choices

If you do not want typed actions sent for processing, simply do not use the "Do anything…" text box; the rest of the game is fully playable without it and works entirely offline.

## Changes

This policy may be updated as the Application changes. Continued use after an update constitutes acceptance of the revised policy.

## Contact

Questions about this policy: Eliteviber@outlook.com
