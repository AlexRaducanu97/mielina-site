# Mielina privacy policy

_Last updated November 7, 2026_

## In short

Everything you log in Mielina stays on your phone. The app has no account, no analytics, no ads and no server of its own. It connects to the internet only for the MS news and, if you turn it on, the weather forecast, and neither request carries anything from your journal. Dictation turns speech into text on the phone where it can, and sends what you say to online speech recognition only if you allow it. Health data from Apple Health or Health Connect is read only if you turn that on, and stays on the phone too.

## What stays on your phone

Your symptom entries and relapses, daily check-ins, treatments with the dose log and injection sites, check-ups with their notes, monthly questionnaires, symbol matching, dot tapping and two-minute walk tries, the forecast days kept for your place, the steps, sleep and walking speed read from Apple Health or Health Connect if you turned that on, your reminders and your settings, including the name printed on the PDF and the questions for the neurologist. They are kept in the app's own storage on the phone, which other apps can't read.

The PDF report is made on the phone when you ask for it and goes only where you share or print it. Deleting the app deletes everything it holds, apart from the backups and PDFs you saved elsewhere.

If you turn on Settings › Health data, Mielina reads your steps for each day, the time you slept each night and, on an iPhone, your walking speed from Apple Health or Health Connect, for the last 30 days at a time, and keeps them on the phone beside your journal, where the daily check-in, the Journal's week, the insights and the PDF show them. It reads only what you allow in the phone's own permission screen, never writes anything to the health app and never sends this data anywhere. Turning it off stops the reading, and the same page can delete what was read.

For the home-screen widget, the app keeps a copy of what the widget may show, in storage that only the app and its widget read: the doses of about the coming week, with their names, types, times and injection sites, and how much of today's check-in is answered. Once you add the widget, it shows the next dose and the check-in on the home screen, which the phone's home screen app draws, where anyone who sees the screen can read them; on an iPhone's Lock Screen it shows only the day and time of the next dose, or a short message such as that all your treatments are paused, never a treatment's name, type or injection site. Settings › Widget can hide the names and sites.

During a two-minute walk, the app counts your steps for those two minutes only: on Android from the phone's motion sensor, which asks no permission; on an iPhone from the iPhone's own step count, once you allow Motion & Fitness. While the walk runs, the lock screen shows its time left where the phone allows it (on Android while the app's notifications are allowed, on an iPhone from iOS 17.6), and the screen stays on only where the walk can't go on with the phone locked. Only the number of steps is kept, with the day, the time and the walking aid you chose; nothing else is recorded from the sensor or the step count, and neither is read at any other time, except once when the iPhone first asks for Motion & Fitness (see below).

When something in the app fails, such as a reminder that couldn't be set, the app notes it in a log on the phone: when, the app's version, where in the app and the error's own words, without the values that were being saved. It keeps the last 50, and only About › Report a problem reads them, to show them to you and to put them into the email you write.

## What leaves your phone

Only the news and the weather requests go out from the app, each carrying your IP address, as every internet connection does, and what you dictate, only once you allow online speech recognition. Links, Add to calendar and Report a problem hand something to another app, as below.

- **News.** To show MS news, the app downloads Google News' public search feed for “multiple sclerosis” in the app's language. The request carries those search words and the language, nothing about you. Google's privacy policy applies to what Google sees.
- **Weather.** Only once you choose a place on Settings › Weather, the app asks Open-Meteo for that place's forecast: the town's coordinates, or your phone's location rounded to about 10 km if you chose Use my approximate location. The exact position is never kept or sent. While the morning heat alert is on, the app also asks for that forecast in the background about twice a day, so that the alert follows it on days you don't open the app; that request carries the same place and nothing else. Typing a town's name sends the letters typed to Open-Meteo's town search. Turning the forecast off stops every request, and turning the heat alert off stops the ones in the background.
- **Dictation.** The microphone in an entry's notes and a relapse's treatment turns what you say into text with the phone's own speech recognition. Where the phone can do that by itself in the app's language, nothing you say leaves it. Where it can't, the app asks you first before using online speech recognition: Apple's on an iPhone, or on Android the phone's speech service, Google's on most phones, which then receives what you say while the microphone listens, under its own privacy policy. Nothing else from your journal is sent, the app keeps only the text, and Settings › Dictation turns the online recognition off.
- **Links.** News stories and the trusted sites open in your browser, where that site's own privacy policy applies.
- **Calendar.** Add to calendar hands a check-up's name, its due day and how often it repeats to your calendar app, and nothing else.
- **Problem reports.** About › Report a problem opens an email in your own email app, with the app's version, the phone's system and model, the app's language and the errors noted. You read it, can change it and send it yourself; the app sends nothing by itself, and the email app's own privacy policy applies.

## Backups

A backup is made only when you ask for one, as a single file that you save or share where you choose, such as your files, a cloud drive or an email. The app never uploads it anywhere itself, and never deletes a backup you saved.

You can protect the file with a password. It is then encrypted with AES-256-GCM, with a key made from the password by Argon2id, and the password is never stored, so a forgotten one can't be recovered. Without a password, anyone who gets the file can read it.

Your phone's own backup, iCloud on an iPhone or Google's backup on Android, may include the app's data like any other app's. That is set in the phone's settings and covered by Apple's or Google's terms.

## Notifications and permissions

Reminders are scheduled on the phone itself; no notification comes from a server. The app asks for:

- **Notifications.** For the medication reminders, the daily check-in, the check-ups, the heat alerts and the two-minute walk: on Android its time left on the lock screen, on an iPhone its start and end. A treatment's or a check-up's reminders are set with it, the heat alert's switch is on Settings › Weather, and Settings › Reminders has the switch for every other prompt.
- **Alarms and reminders (Android).** So that a reminder rings on the minute. Without it, a reminder may be a few minutes late.
- **Approximate location.** Only if you choose Use my approximate location for the weather. It is read once, when you choose it, rounded to about 10 km, and only the rounded position is kept; choosing it again reads it again.
- **Microphone and speech recognition.** Only when you first tap the microphone in a note, to hear what you dictate while it listens; an iPhone asks for speech recognition too. The app keeps only the text.
- **Calendar.** Only when you add a check-up to your calendar. The calendar screen that opens belongs to the phone and may ask for access to your calendar, and on an iPhone to your contacts; Mielina itself never reads your calendar or contacts.
- **Health data.** Only if you turn on Health data, on the welcome at the first start or in Settings: to read steps, sleep and, on an iPhone, walking speed from Apple Health or Health Connect. Read only, never written, and you can take it back at any time in the Health app (Sharing › Apps) or in Health Connect (App permissions).
- **Motion & Fitness (iPhone).** Only when you first start a two-minute walk on an iPhone: to read the iPhone's own step count for the two minutes of a walk. The iPhone asks with a first read of the second before that walk, which the app throws away. You can take it back at any time in the iPhone's Settings › Privacy & Security › Motion & Fitness.

## What the app never does

No account or sign-in. No analytics, tracking or advertising, and no crash reports sent by the app itself: the errors it notes leave the phone only in a problem report you send yourself. No data sold or shared. Nothing from your journal leaves the phone unless you back it up or share a PDF yourself, and what you dictate only through the online speech recognition you allowed.

## Your choices

Swipe an entry, a treatment, a check-up, a day done, a questionnaire, a symbol matching, dot tapping or two-minute walk try to delete it; a dose or a check-in answer is changed from its own row. Every prompt can be turned off: a treatment's or a check-up's reminders with it, the heat alert and the forecast on Settings › Weather, the health data on Settings › Health data, the microphone and its online speech recognition on Settings › Dictation, and the others in Settings › Reminders. The widget's names and sites can be hidden on Settings › Widget, and removing the widget from the home screen takes it away. The errors noted can be read and cleared on About › Report a problem. Deleting the app removes everything it holds on the phone.

## Changes to this policy

This policy changes when the way the app handles data changes, and the date at the top says when. The current version is always in the app, under About › Privacy policy, and on the web at https://alexraducanu97.github.io/mielina-site/privacy.html.

## Who makes Mielina

Mielina is made by Alex Raducanu as a personal project, not by a company. Questions about privacy can be sent to the developer at mielina.support@gmail.com, the contact on the app's store page too.

---

The app shows this same text under Settings › About Mielina › Privacy policy.
