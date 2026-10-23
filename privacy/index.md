---
layout: default
title: Ruy Lopez privacy policy
---

# Privacy Policy — Ruy Lopez

**Last updated:** 2026-10-23
**Contact:** jonathan@nullmening.org

---

## The short version

Ruy Lopez is a chess learning app. It asks for a nickname and nothing else. It has no
accounts with passwords, no email addresses and no advertising. Your games are stored on
your own phone. It sends anonymous counts of app opens and finished games, and a report when
it crashes. A build with online services enabled creates an anonymous
session when it can reach the server. Leaderboard participation and reports send the
additional information described below.

---

## What we collect

**A nickname you choose.** Displayed publicly on the leaderboard. Do not use your real name
if you would rather not be identified.

**Your rating and game results.** When you join the leaderboard, the app sends your rated game results
(which bot, win or loss, your rating before and after, hints used,
how much of the opening was played from the book) and the moves of the game
in standard chess notation (PGN). Game moves are stored so that
leaderboard entries can be verified. Results played before choosing a nickname wait on
your phone and are uploaded if you join later. Unrated games are not uploaded.

**An anonymous account identifier.** Created automatically when online services connect,
including before you choose a nickname, and kept in the app's session on your phone. It
identifies your online account and reports; it is not a hardware or advertising identifier.
The app does not ask for a real name, email address or phone number.

**Tip reports.** If you report an explanation as incorrect, we receive the chess position,
the explanation text, and any comment you add.

**Name reports.** If you report a nickname on the leaderboard, we receive that nickname, any
comment you add, and the anonymous identifier of whoever reported it, so that one person
reporting the same name twice counts once. Deleting your account removes the identifier from
reports you made; the report stays.

**Anonymous usage counts.** That the app was opened; that the introduction was finished
or skipped, at which page and with the level you chose; that a game was started, with the
opening (an opening of your own counts only as "own"), the bot's rating, your colour and
whether it was rated; that a game was finished, with its result and whether it was rated;
that a Practice session was finished, with how many positions you found alone; that a game
was analysed; that you made an opening of your own (never its name); and that you chose a
nickname (never which). Each count carries the app version and the platform. Each count carries
a random number that is made when the app starts, is never stored and is forgotten when the
app closes. Nothing in it identifies you or your phone, and no profile is built from it.

**Crash reports.** When the app crashes, it sends the error and where in the code it
happened, the app version, the phone model and Android version, and technical details such
as memory at the time. A report contains no nickname, games or account identifier, and the
app sets Sentry not to collect default personal data or screenshots.

## What we do not collect

No email addresses. No passwords. No real names. No phone numbers. No location. No contacts.
No photos. No device identifiers or advertising IDs. No analytics beyond the anonymous
counts above, and no tracking across apps or websites. No payment information — the app is free and has no purchases.

**There is no advertising in this app, and no data is shared with advertisers or data
brokers.** There are no advertising or analytics SDKs. The Supabase SDK provides the
online functions described in this policy, and the Sentry SDK sends crash reports. The
anonymous counts are sent over plain HTTPS without an SDK.

---

## What stays on your phone

Most of it:

- Every game you have played, move by move
- Your rating history and statistics
- Your record against each bot and in each opening
- What Practice remembers of the positions you have met, and the days you practised
- Analysis results
- Openings you made or copied yourself
- Positions you saved to play from later
- All settings

Apart from rated results uploaded after joining the leaderboard, reports you choose to
send, and the counts and crash reports above, the app stores this data locally.

**Android device backup.** Depending on your device and backup settings, Android may
include app data in a cloud backup (such as Google Drive) or a device-to-device transfer.
This can include your game history, settings and saved account session. Ruy Lopez does
not receive these system backups. Installing the app again or moving to another device
may restore saved data. Uninstalling removes the app's local data; it does not delete a
system backup or request deletion of an existing online account.

---

## Where data goes

**Supabase** hosts the leaderboard database. They process data on our behalf as a service
provider: <https://supabase.com/privacy>

Connecting to the service also sends the network information needed for HTTPS, such as
your IP address. The app does not use it to determine your location. Browsing the
leaderboard contacts the service even if you have not chosen a nickname.

**PostHog** receives the anonymous usage counts, on servers in the EU, and processes them
on our behalf: <https://posthog.com/privacy>. The app tells PostHog not to look up a
location from the connection.

**Sentry** receives crash reports and processes them on our behalf:
<https://sentry.io/privacy/>.

Both see the connection's IP address, which is needed to deliver the data.

**Lichess** is **not** contacted by the app. Opening data is downloaded once by the
developer during development and shipped inside the app. Playing does not send anything to
Lichess.

**Stockfish** runs entirely on your phone. Your moves are never sent anywhere to be
analysed.

We do not sell data. We do not share it with anyone except the three providers above.

---

## Children

The app is suitable for all ages and contains no advertising, no purchases and no
communication between users.

Because nicknames appear publicly on a leaderboard, children should be advised not to use
their real name. Nicknames are filtered for offensive content, and anyone can report a
tip or a name — a name by tapping it on the leaderboard.

---

## Your rights

**See your data.** Your games and statistics are visible in the app. For your leaderboard
record, contact us.

**Delete your data.** Settings → *Delete my account and data*. This removes your
leaderboard entry, your results and your nickname from the server, and erases everything
stored on your phone. **It is immediate and cannot be undone.**

**Play offline.** Games, coaching, practice and analysis work without an internet
connection. Leaving your nickname blank keeps your results off the public leaderboard;
it does not disable anonymous sign-in, leaderboard reads or reports you choose to send.

Choosing a nickname joins the public leaderboard. Withdraw your participation at any
time by deleting your account. You can also contact the address above to request access
to or deletion of server data; we need to verify ownership before acting on a request.

---

## Retention

Anonymous usage counts are kept for up to one year, and crash reports for up to 90 days.
Leaderboard entries are kept until you delete your account. Tip reports are kept until the
tip is corrected, then deleted. Name reports are kept until they have been looked at, then
deleted. Local data lives on your phone until you delete the account
or uninstall the app.

---

## Security

Data is transmitted over HTTPS. Database access is restricted by row-level security so that
one player cannot read or modify another player's record.

Ratings are calculated on your phone, which means a determined user could submit a false
rating for themselves. The leaderboard is intended as friendly motivation, not a
competitive ranking. It is not possible for anyone to alter *your* entry.

---

## Changes

Material changes will be announced in the app's release notes, with the date above updated.

---

## Open source

Ruy Lopez is licensed under GPL-3.0. Corresponding source is supplied with distributed
releases. The app repository is scheduled to become public with the Android launch:
https://github.com/Snickers-Bar74/RuyLopez
