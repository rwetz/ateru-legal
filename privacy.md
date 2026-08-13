---
title: Privacy Policy — Ateru
---

# Privacy Policy

**Ateru is an anime tracker that keeps your library on your device. It has no
accounts, no servers, and collects nothing about you.**

Last updated: 13 August 2026.

---

## The short version

- **No account.** There is nothing to sign up for and nothing to sign in to.
- **No analytics, no tracking, no advertising.** The app contains no analytics SDK,
  no crash reporter, no advertising identifier and no third-party tracker of any
  kind.
- **Your library never leaves your device** unless you export it yourself.
- **One external service.** Anime titles, cover art, episode counts and airing
  schedules come from AniList's public API.

---

## What Ateru stores, and where

Everything Ateru knows about you is in a database file on your device, inside the
app's own storage:

- The series in your library, their status, your episode progress, your scores and
  your notes
- Your watch history — which episode you marked watched, and when
- Your settings
- A cache of cover art and of anime details fetched from AniList

None of it is transmitted anywhere. It is not backed up to a server we control,
because there is no server we control. If you delete the app, it is gone — which is
also why Ateru has an export feature.

## What leaves your device

**Requests to AniList, and nothing else.** When you search for a series, open one, or
let Ateru refresh what it already has, the app asks
[AniList](https://anilist.co)'s public API for that information, and loads cover
images from AniList's servers.

Those requests carry what any web request carries — your IP address and the query
itself. They do **not** carry your library, your progress, your notes, your scores or
any identifier created by Ateru, because Ateru does not create one. AniList cannot
tell that two requests came from the same person via anything Ateru sends.

AniList is an independent service with its own privacy policy, which you can read at
[anilist.co/terms](https://anilist.co/terms). **Ateru is not affiliated with
AniList.**

## What you can send, if you choose to

Two features move data off your device, and both require you to act:

- **Export.** Ateru writes your library to a file and hands it to the iOS share
  sheet. Where it goes from there — Files, AirDrop, a message — is your choice. It
  goes nowhere by itself.
- **Import.** You pick a file — for example a MyAnimeList export — and Ateru reads
  it. The file is read on your device and is not uploaded.

## What Ateru does not do

- No advertising, and no advertising identifier (IDFA). Ateru never requests
  tracking permission because it has nothing to track you with.
- No analytics or telemetry of any kind.
- No crash or performance reporting.
- No sale or sharing of personal information, because none is collected.
- No location, camera, microphone, contacts or health access. Ateru requests none of
  these permissions.

## Children

Ateru is not directed at children and collects no personal information from anyone,
including children under 13. There is nothing to delete on request, because there is
nothing held.

## Your rights

Because Ateru holds no data about you on any system we operate, requests to access,
correct, export or delete your data have nothing to reach. You already have all of
it:

- **Access and export** — Settings → Data → Export
- **Deletion** — Settings → Data → Clear library, or delete the app

## Changes

If this policy changes, the updated version will be posted here with a new date. The
full history of this document is public in the repository that serves it, so any
change can be seen rather than taken on trust.

## Contact

Questions about this policy: **rwetz00@gmail.com**
