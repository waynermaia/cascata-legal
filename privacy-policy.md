# Cascata Privacy Policy

**Version:** 2.0 · **Last updated:** November 24, 2026

This policy explains what personal data the Cascata app handles, where it comes from, what it is for, who it is shared with, how long it is kept and how you exercise your rights. It applies together with the Cascata Terms of Use.

Giving data is always your choice. Some features, however, do not work without it: for example, without signing in there is no way to take your progress to another device.

---

## Summary

- Profiles and progress stay **on your device**. If you sign in with Google, they are also kept in your account so they reach your other devices.
- The **microphone** is used to recognise notes, **on the device and in real time**. Practice sound is not recorded or sent. The exceptions are things you ask for yourself: recording a video, sending spoken feedback about a lesson or importing a recording.
- We send **usage statistics** tied to a random install code, **without your name, e-mail, age, typed text or location**. You can turn this off in Settings.
- The **teacher** and the **natural voice** run **on the device itself**. The conversation only leaves the phone if you turn on, in the Lab, the teacher through the API with your own Anthropic key.
- **Children** use the app through a profile created by a responsible adult.
- **We do not sell** data, **we do not advertise**, we do not use the device's advertising identifier and we do not use your data to train artificial intelligence.
- You can ask for access to, correction of, a copy of or deletion of your data at any time.

---

## 1. Who looks after your data

**Controller:** WAYNER MAIA VITORINO, sole proprietorship (empresário individual), CNPJ 32.593.331/0001-79, Rua Vinte e Um de Abril, 187, Pacaembu, Uberlândia/MG, CEP 38401-574, Brazil. In this policy, "we" and "Cascata" mean him.

**Data protection officer (encarregado, DPO):** Wayner Maia, at **contato@cascata.pro** or at the address above.

This policy applies to everyone who uses the Cascata app on iPhone, iPad or Android, in any country, to the parents and guardians of children and teenagers who use the app, and to anyone who writes to us by e-mail. It does not cover other companies' websites and services that you open from the app; those have their own policies.

We follow Brazil's General Data Protection Law (LGPD, Law 13,709/2018). The policy also covers what the GDPR (Europe and the UK), US state privacy laws and COPPA (children in the US) ask for. See sections 11 and 12.

---

## 2. What data we handle and why

The data is grouped by what you do in the app. For each group we say what it is, where it comes from, what it is for, its legal basis under the LGPD and where it is kept. Retention periods are summarised in section 7.

Some features exist only in certain versions of the app, or sit under **Settings > Lab** while they are being tested. They are described here anyway, and the description applies whenever the feature is available to you.

### 2.1 Family profiles and first answers

- **What data:** each person who plays has a profile (up to six on the same device, under **Settings > Family**). The profile holds a name or nickname (it can be made up), age, avatar and the first answers: piano experience, goal, motivation, instrument, time per day, days per week, sheet-music reading, first song, reminder time and how you heard about Cascata.
- **Where it comes from:** you type or choose it.
- **What for:** greeting the person by name, building the path and the study pace, keeping each person's progress apart and suiting the lessons to the age of who plays.
- **Legal basis:** performance of a contract (art. 7, V). For children, see section 10.
- **Where it is kept:** on the device. It only leaves the device if you sign in (section 2.3).

### 2.2 Progress, practice and settings

- **What data:** path steps (stars, attempts, when mastered), songs played (accuracy, stars, number of times), recent sessions, days in a row of practice, XP, time practised per day, daily goal, challenges, saved songs, looped passages, calibrations and settings. Also the MIDI and MusicXML files you import, the lessons of imported songs, the videos you record and a recent history of usage events (up to 300 on iPhone and 50 on Android).
- **Where it comes from:** your use of the app.
- **What for:** showing your progress, picking up where you left off and fitting the path to what you already know.
- **Legal basis:** performance of a contract.
- **Where it is kept:** on the device, until you delete the profile, clear the app's data or uninstall it. It leaves the device only through the routes in sections 2.3 to 2.10.

### 2.3 Account and sync (optional)

- **Account data:** if you sign in with Google, we receive from Google the account identifier, name, e-mail and the address of the account photo. Today Google is the only way to sign in.
- **Synced data:** one document per account with the profiles (name, age, avatar and first answers), each profile's progress and settings (section 2.2, without the files), XP, time practised, goals and challenges. Progress stores each song's identifier; for an imported MIDI or MusicXML file, that identifier contains the file name. We do not sync audio, videos, music files, keys, the conversation with the teacher, or the name and e-mail of the Google account.
- **Where it comes from:** from Google, at sign-in, and from your use of the app.
- **What for:** creating and keeping the account, and taking your progress to the other devices you sign in on.
- **Legal basis:** performance of a contract.
- **Where it is kept:** the account in Firebase Authentication (Google, USA); the synced document in Cloud Firestore (Google), in São Paulo, Brazil. On the device, the access tokens are kept in the Keychain (iPhone) or encrypted by the Android Keystore (Android). The account photo is loaded straight from Google's servers.
- **For how long:** while the account exists. When you delete the account in the app, the account and the synced document are erased at once.

### 2.4 Usage statistics and identifiers

- **What data:**
  - **usage events:** what you do in the app, such as opening the app, viewing a screen, starting or finishing a practice (with the song, hands, tempo, mode, accuracy, stars, duration and wrong notes), moving along the path, changing a setting or the language, completing a challenge, sharing a result, importing a song (only the kind and whether it worked) and subscribing (which plan). Of profiles, only the number of profiles created, switched or deleted;
  - **install identifier:** a random code the app creates the first time it opens. It is not the device's advertising identifier;
  - **technical data:** app version, operating system and version, language, A/B test groups, features turned on and short technical messages when sync fails;
  - **link to the account:** if you sign in, the account identifier is linked to the install identifier;
  - **IP address:** it arrives with the connection. The app asks the statistics service **not to infer your location** from it.
- **What we do not send:** profile name, age, e-mail, phone number, the text you type, the conversation with the teacher, links, titles of songs imported by link, audio and location. One caveat: the identifier of a MIDI or MusicXML file you imported contains the file name and may appear in some events.
- **What for:** understanding how the app is used, finding and fixing faults, comparing versions and improving the lessons.
- **Legal basis:** legitimate interest (art. 7, IX), with the option to turn it off. For children, see section 10.
- **Where it is kept:** PostHog, in the USA, for 12 months.
- **How to turn it off:** **Settings > Privacy > Send usage data**. Sending is on by default and, once you turn it off, the app stops sending. The recent history stays only on the device, so you can attach it to a problem report.

### 2.5 Microphone, MIDI keyboard, camera and videos

- **Microphone:** the app listens to the piano to recognise the notes **on the device and in real time**. Practice sound stays only in memory and is not recorded or sent. The microphone only records when you ask: in a video (below), in spoken feedback (section 2.6) or in a recording you choose to import (section 2.7).
- **MIDI keyboard:** by cable or Bluetooth, the app reads the notes you play. They do not leave the device. On Android, the search for Bluetooth keyboards is not used to locate you.
- **Camera and screen:** if you record a video of yourself playing, the app uses the camera, the screen and the microphone. The video stays on the device and only leaves it if you share it or save it to your gallery.
- **Legal basis:** performance of a contract. Permissions are requested by the operating system and you can withdraw them at any time in the device settings.

### 2.6 Spoken feedback about a lesson (in some versions)

This feature only appears in versions of the app connected to Cascata's lesson server and may not exist in the version you downloaded from the store.

- **What data:** a recording of your voice, up to 5 minutes long, which only starts when you tap the microphone and is only sent when you tap **Send**. The lesson context goes with it: the song (identifier and title), the path step, hands, mode, bar, speed, input type, display settings, the note-by-note log of the attempt, the operating system, the device model, the app version and the date and time. The install identifier and the account identifier do not go.
- **What for:** understanding what worked or did not work in the lesson, and fixing it. The recording is transcribed automatically on our own server, without passing through any other company.
- **Legal basis:** consent (art. 7, I), which you give by recording and sending. You can withdraw it by asking for deletion (section 6).
- **Where it is kept:** on Cascata's server, in Brazil, for up to 90 days after it is sent.
- We do not use your voice to identify you or to train artificial intelligence.

### 2.7 Imported music and sheet-music search (in some versions)

These features also depend on Cascata's lesson server and may not exist in the version you downloaded. Importing MIDI and MusicXML files always works, and only on the device.

- **What data:**
  - **by link:** the link you paste (while you type, to show the title and the cover) and, when you confirm, the link, the title and the chosen excerpt;
  - **by recording or file:** only the sound (from a video, the sound is separated on the device) and the title, which starts as the file name and which you can change;
  - **sheet-music search:** the text you type in the search;
  - the IP address of the connection.
- **What for:** getting the sound, separating the instruments, writing out the notes and returning the lesson to you alone, or showing free sheet music that matches the search.
- **Legal basis:** performance of a contract.
- **Where it is kept and for how long:** on Cascata's server, in Brazil. The heaviest steps (separating the instruments and writing out the notes) may be done by Modal Labs, in the USA, on our behalf. The audio and the separated tracks are deleted as soon as the lesson is ready or processing fails. The lesson files and the record of the request (link or file name, and title) are deleted within 24 hours. Search answers stay only in the server's memory, for up to 1 hour. The finished lesson is kept only on your device.
- **Straight from the device to other sites:** to show a link's title and cover, the app may query the link's own site (for example, YouTube) and download the cover image. When you open sheet music found in the search, the app downloads the file from the Mutopia Project. These sites receive the device's IP address and what was requested, under their own policies.

### 2.8 Teacher and voice

- **On the device:** the teacher (Gemma 4 model, by Google) and the natural voice (Supertonic 3 model, by Supertone) run on your phone. The conversation and the practice report do not leave the device.
- **Model downloads:** the files come from Hugging Face (USA), which receives the IP address as with any download. The teacher is only downloaded when you ask. The natural voice may be downloaded on its own, in the background and, by default, only on Wi-Fi, after the teacher first speaks with the system voice. If you delete the voice in Settings, it is not downloaded again.
- **Teacher through the API, with your own key (Lab):** if you turn on this option under **Settings > Lab**, enter an Anthropic key and do not have the on-device teacher, the practice report (song title, accuracy, errors per bar, timing) and your messages go **straight from the device to Anthropic**, in the USA. The key stays only on the device, in the Keychain or the Android Keystore. We do not receive or keep this conversation; Anthropic handles it under its own rules and the contract you have with it. This option is not for children.
- **Legal basis:** performance of a contract.

### 2.9 Problem reports and support

- **Problem report:** opens when you shake the device or under **Settings > Help**. It carries the text you write, a screenshot (attached by default; you can remove it), the app version, the device model, the operating system, the language, the screen you were on, the install identifier and the last 20 usage events recorded on the device. The app sends nothing by itself: it opens your e-mail app or the share sheet, you see the content and decide whether to send it.
- **Requests by e-mail** (support, account deletion, rights): your e-mail address and what you write.
- **What for:** answering, fixing the problem and showing that we handled the request.
- **Legal basis:** performance of a contract, legitimate interest and compliance with a legal obligation (art. 7, II).
- **Where it is kept:** in our mailbox. Problem reports for up to 2 years after they are resolved; support and rights requests for 5 years (the limitation period of Brazil's Consumer Defence Code).

### 2.10 Subscription and purchases

- **What data:** purchases are made in the App Store (Apple) or Google Play (Google). **We do not receive the card number, the billing name or the address.** The app receives from the store, on the device, the plan, whether the subscription is active, the dates and the proof of purchase, which may be checked on the device itself. In the statistics, we record that a subscription happened and for which plan.
- **What for:** unlocking paid content and knowing how many people subscribe to each plan.
- **Legal basis:** performance of a contract; legitimate interest, for the statistics.
- **Where it is kept:** the purchase stays with Apple or Google, under their rules. The status stays on the device. The subscription event stays in PostHog for the statistics period.

### 2.11 Notifications

Practice reminders and the notice that an imported song is ready are scheduled on the device itself. The app does not use a push notification service and does not create a push identifier.

### 2.12 What we do not do

- We do not sell or rent personal data.
- We do not use data for advertising, do not share data with ad networks and have no advertising or marketing attribution SDK.
- We do not use the device's advertising identifier or track you across other companies' apps and websites.
- We do not send marketing e-mails.
- We do not collect precise location.
- We do not ask for sensitive data (such as health, religion or biometrics). The voice in feedback is not used to identify anyone.
- We do not make automated decisions that have legal effects on you.
- We do not use your conversations, recordings, the content you send or the generated lessons to train artificial intelligence models, and we do not allow our processors to do so.

---

## 3. How we collect data

- **From you:** when you create a profile, answer the first questions, write a report, record feedback, import a song or send us an e-mail.
- **Automatically:** through your use of the app, with the permissions you gave (microphone, camera, Bluetooth, notifications) and through usage statistics.
- **From other companies:** from Google, when you sign in with your Google account; from Apple or Google, about your subscription; and from the sites the imported links come from (title and cover).

---

## 4. Cookies, SDKs and other technologies

- The app **does not use cookies** or session-recording technologies.
- The app **has no advertising, marketing attribution or social media SDK.**
- Other companies' services that the app uses and that receive data:
  - **sign-in:** Google Sign-In (iPhone), Credential Manager and Google Play services (Android), and Firebase Authentication;
  - **sync:** Cloud Firestore (Google);
  - **statistics:** PostHog, called directly through its API, without an SDK;
  - **purchases:** StoreKit (Apple) and Google Play Billing (Google);
  - **model downloads:** Hugging Face;
  - **teacher through the API, if you turn it on:** Anthropic.
- The app's other libraries (animations, effects, sound) work only on the device and send no data.
- **Lab:** under **Settings > Lab** you can turn on features that are still being tested. They follow this policy.

---

## 5. Who we share data with

**Processors.** Companies that handle data **on our behalf, following our instructions**, and that cannot use it for their own purposes:

- **PostHog Inc.** (USA): usage statistics.
- **Google** (Firebase Authentication, USA; Cloud Firestore, Brazil), only for those who sign in: sign-in and sync.
- **Modal Labs, Inc.** (USA), only for those who import songs, in versions that have the feature: separating the instruments and writing out the notes. It uses the audio only during processing.
- **Hugging Face** (USA): hosts the teacher and voice files you download.

**Stores.** Apple and Google distribute the app and handle payments, as independent controllers, under their own policies.

**At your initiative.** When you share a video or a result (through the share sheet, the gallery or Instagram), send a report through your e-mail app or turn on the teacher through the API with your Anthropic key, the data goes to whoever you chose, and from then on its handling follows that service's rules.

**By obligation or for defence.** When the law or an order from an authority requires it, to protect our rights or other people's rights in legal proceedings, or to investigate fraud or illegal use of the app.

**In a sale or reorganisation** of the app, the data may pass to the new owner, who must keep the protection of this policy.

We do not sell personal data or share it for advertising.

---

## 6. Your rights and how to exercise them

You (or the parent or guardian, for children and teenagers) may, at any time and free of charge:

- confirm whether we handle your data and access it;
- correct incomplete, wrong or outdated data;
- ask for anonymisation, blocking or deletion of data that is unnecessary, excessive or handled against the law;
- receive your data in a structured format to take to another service (portability);
- ask for deletion of data handled on the basis of consent, and withdraw consent;
- know who we share your data with;
- know what happens if you do not give consent;
- object to handling based on legitimate interest;
- ask for a review of decisions made only by automated means;
- complain to Brazil's **National Data Protection Authority (ANPD)**, at gov.br/anpd, or to the data protection authority of your country.

### In the app

- **Turn off statistics:** Settings > Privacy > Send usage data.
- **Correct or delete a profile:** Settings > Family. Deleting a profile deletes its path, progress and settings on the device and, if you signed in, also in the synced copy.
- **Delete the downloaded teacher and voice:** Settings > On-device teacher.
- **Withdraw permissions** (microphone, camera, Bluetooth, notifications): in the device settings.
- **Delete the account:** Settings > Account > Delete account. The account and the synced progress are erased at once, and the app opens a pre-filled e-mail to us with the install identifier, so we can also delete the statistics.
- **Delete the data on the device:** clear the app's data in the system settings or uninstall the app.

### By e-mail

For any other request, including without an account, write to **contato@cascata.pro**. Because statistics and spoken feedback carry no name or e-mail, to find them we need the install identifier (which the app puts in the deletion e-mail and in the problem report) or, for spoken feedback, the approximate date and the song.

We may ask for information to confirm that the request is yours or from someone you represent. If you act through a representative, they must show they are authorised. We answer within **15 days**, or within the shorter period required by the law of your country. If we cannot fulfil a request, we will tell you why and how to challenge it.

---

## 7. How long we keep data

- **Data on the device:** until you delete the profile, clear the app's data or uninstall it.
- **Account and synced progress:** while the account exists; erased at once when you delete the account in the app, or within 15 days of a request by e-mail.
- **Usage statistics:** 12 months.
- **Spoken feedback:** up to 90 days after it is sent.
- **Imported music:** audio deleted at the end of processing; lesson files and request record within 24 hours; searches, up to 1 hour in memory.
- **Problem reports:** up to 2 years after they are resolved.
- **Support and rights requests:** 5 years.
- **Purchase data:** with Apple or Google, for their periods and under tax law.

After these periods we delete or anonymise the data, unless the law requires us to keep it longer or it is needed to defend rights in legal proceedings. We may delete data before these periods when it is no longer needed.

---

## 8. International transfers

Some processors are outside Brazil, mainly in the USA (PostHog, Google Firebase Authentication, Modal Labs, Hugging Face). In those cases, the transfer follows the standard contractual clauses approved by the ANPD (Resolution CD/ANPD No. 19/2024) or another mechanism in art. 33 of the LGPD. For people in the European Economic Area, the UK or Switzerland, we use the European Commission's standard contractual clauses (with the UK and Swiss addenda) or the EU-US Data Privacy Framework, when the processor takes part in it.

The synced document and the lesson server are in Brazil.

---

## 9. Security

- The app's communications with the services in section 5 use encrypted connections (HTTPS/TLS).
- The account access tokens, and the Anthropic key if you use one, are kept in the iPhone Keychain or encrypted by the Android Keystore.
- On Android, the app's data is excluded from Google backup. On iPhone, iCloud may include the app's data in the backups you turned on; those backups are made by Apple, under your account.
- The teacher and voice files are checked against a digital fingerprint (SHA-256) after download.
- We give access to data only to those who need it and require the same of our processors.
- If you think someone got into your account, sign out in the app, change your Google account password and tell us at contato@cascata.pro.
- No system is completely secure. If there is an incident that may bring you relevant risk or harm, we will notify you and the ANPD, as the law requires.

---

## 10. Children and teenagers

Cascata may be used by children and teenagers, **always through a responsible adult**.

- **The adult sets it up.** Whoever installs the app, creates the profiles, signs in, subscribes and accepts the Terms is an adult: the father, mother or legal guardian. The child uses the app in a profile the adult creates under **Settings > Family**.
- **What the child provides.** The profile asks only for a name or nickname (it can be made up, and we recommend not using the full name), age and an avatar, plus the first answers. During use, the app keeps the child's progress on the device.
- **What leaves the device.** If the adult signs in, the child's profile and progress go into sync (section 2.3). If statistics are on, the device's usage events go to PostHog without the child's name or age. The adult can turn statistics off under **Settings > Privacy**.
- **Consent.** By creating a child's profile, the adult states that they are the parent or guardian and authorises the use described in this policy. We always handle children's and teenagers' data in their best interest (art. 14 of the LGPD and Brazil's Child and Adolescent Statute) and only what the app needs to work.
- **Features for the adult.** Spoken feedback (section 2.6) should be recorded by the adult or with the adult nearby. The teacher through the API with your own key, the Lab and purchases are for adults.
- **No advertising.** We do not advertise to or build commercial profiles of children and teenagers.
- **The parent's rights.** The parent or guardian can, at any time, view, correct or delete the child's profile under Settings > Family, turn statistics off and ask for deletion of any of the child's data, or withdraw consent, at contato@cascata.pro.
- **Other countries.** In the USA, these rules apply to children under 13 (COPPA). In Europe, up to the age set by each country (13 to 16).
- If we learn that we handled a child's data without a parent's or guardian's authorisation, we will delete that data.

---

## 11. For US residents

This section addresses US state privacy laws, such as those of California (CCPA/CPRA), Colorado, Connecticut, Virginia and Utah.

- **Categories of data collected in the last 12 months:** identifiers (install identifier, account identifier, e-mail, IP address); account personal data (name); commercial information (plan subscribed); app activity (usage events); audio (spoken feedback and imported songs, in versions that have these features); and profile data (name or nickname, age, first answers). Sources, purposes and recipients are in sections 2, 3 and 5.
- **Sale and "sharing":** we do not sell personal data and do not share it for cross-context behavioural advertising. So there is no "do not sell" option to offer. We also do not use sensitive data to infer characteristics about you.
- **Your rights:** to know and access, correct, delete, receive a portable copy and not be discriminated against for exercising these rights. You can make a request at contato@cascata.pro, directly or through an authorised agent.
- **Verification and appeal:** we verify the identity of whoever makes the request. If we refuse it, you can appeal by writing to the same e-mail with the subject "Appeal"; we answer within the period set by your state's law. If the appeal is denied, you can complain to your state's Attorney General.

---

## 12. For residents of the European Economic Area, the UK or Switzerland

- **Legal bases (GDPR art. 6):** performance of a contract, for the profile, progress, account, sync, import and purchases; legitimate interest, for usage statistics and problem reports (our interest is keeping the app working and improving it, and you can object by turning statistics off); consent, for spoken feedback; legal obligation, for keeping records the law requires.
- **Rights:** besides those in section 6, you have the right to restriction of processing and to complain to the data protection authority of the country where you live or work.

---

## 13. Changes to this policy

We may update this policy when the app or the law changes. The version in force is always in the app (Settings > About) and on Cascata's public page, with the date of the last update. If the change is relevant, we will tell you in the app before it takes effect and, when the law requires, ask for your consent again. A feature that sends new data off the device only enters the app after it is described here.

---

## 14. Contact

- **Controller and data protection officer (DPO):** Wayner Maia, **contato@cascata.pro**
- **Address:** WAYNER MAIA VITORINO, Rua Vinte e Um de Abril, 187, Pacaembu, Uberlândia/MG, CEP 38401-574, Brazil
