# Typekeeper: Path to the Crown Privacy Policy

**Last updated:** October 11, 2026

Typekeeper: Path to the Crown (“Typekeeper”, “we”, “us”) is a single-player typing game developed by FoxForge Studio.

Typekeeper is designed as a local-first game. The current version does not require an account and does not transmit your gameplay data to FoxForge Studio or to third-party analytics, advertising, AI, or cloud-storage services.

This Privacy Policy explains what information the game stores locally, how save files work, and the choices available to you.

---

## Summary

- Typekeeper does not require an account or login.
- Typekeeper does not collect personal information on a FoxForge Studio server.
- Typekeeper does not use advertising.
- Typekeeper does not use analytics or cross-app tracking.
- Typekeeper does not sell player data.
- Typekeeper does not use third-party AI services.
- Game progress and settings are stored locally on your Mac.
- Save import and export happen only when you choose them.
- The current release does not upload your save file or gameplay history to a cloud service.
- Game assets, including music and audio, are bundled with the app.
- The embedded game view blocks navigation to remote web pages.

---

# Information stored locally

## 1) Game progress

Typekeeper stores game progress locally on your Mac.

A local save may contain gameplay information such as:

- unlocked chapters;
- completed stages;
- campaign progress;
- checkpoints;
- scores;
- word counts;
- streaks;
- missed-word counts;
- retries;
- completion results;
- typing speed, including WPM;
- accuracy;
- medals and chapter records;
- score-chase records;
- game mode and pace;
- locally generated gameplay seeds and attempt identifiers; and
- information required to resume or validate saved progress.

This information is used only to provide game functionality such as continuing a campaign, showing records, restoring checkpoints, and displaying local achievements.

Typekeeper does not transmit this gameplay history to FoxForge Studio.

---

## 2) Game settings

Typekeeper stores game preferences locally.

These may include:

- English or Traditional Chinese language preference;
- music and sound settings;
- volume levels;
- gameplay pace;
- motion preferences;
- contrast preferences;
- hints;
- HUD preferences;
- resume-countdown preferences; and
- other game presentation settings.

These settings are used only to remember how you prefer to play the game.

---

## 3) Wardrobe and in-game progression

Typekeeper may store locally:

- virtual coin balance;
- earned and spent virtual currency;
- owned cosmetic items;
- equipped appearance choices;
- reward history;
- progression rewards; and
- related local transaction identifiers used to prevent duplicate rewards.

These are game-state records only.

Typekeeper does not connect this information to a bank account, payment card, brokerage account, or financial account.

The current version does not use Typekeeper accounts or a remote economy server.

---

# Local save storage

## 4) Native save files

Typekeeper's Mac version uses native local files as the authoritative source for durable game progress.

The game stores its save information inside Typekeeper's local Application Support / application-container storage.

The save system may maintain:

- the current progress file;
- a previous valid progress file;
- a damaged-save recovery copy when needed; and
- recovery copies created as part of a player-initiated recovery or reset process.

These additional local copies exist to reduce the risk of losing game progress if a write is interrupted or a save becomes damaged.

They are not uploaded to FoxForge Studio.

---

## 5) Embedded game view

Typekeeper uses Apple's WebKit technology to render the bundled game interface.

The Mac app configures the embedded WebView with a **nonpersistent website data store**.

Durable progress is handled by Typekeeper's native save system rather than ordinary browser cookies or permanent browser storage.

The WebView is restricted to Typekeeper's bundled game resources. Remote main-frame navigation and new browser windows are blocked by the app.

---

## 6) Bundled game assets

Game artwork, music, sound effects, fonts, scripts, and other runtime assets are packaged with Typekeeper.

The game may use WebKit's `fetch` functionality to load bundled audio or other bundled resources through Typekeeper's internal asset scheme.

This is local resource loading and does not send gameplay information to an external web service.

---

# Save import and export

## 7) Exporting a save

You can deliberately choose **Export Save**.

When you export a save, Typekeeper creates a JSON save file containing your game state.

An exported save may include information such as:

- gameplay progress;
- records and scores;
- WPM and accuracy information;
- checkpoints;
- settings;
- wardrobe state;
- virtual currency;
- game version; and
- export time.

The file is created only after you request the export.

Once you save, copy, or share that file outside Typekeeper, the destination you choose controls that copy.

Typekeeper cannot automatically delete exported copies that you have placed elsewhere.

---

## 8) Importing a save

You can deliberately choose **Import Save** and select a compatible Typekeeper JSON backup.

Typekeeper reads only the file you choose through the macOS file-selection process.

Selecting a file does not immediately overwrite your progress. The app validates the selected save and asks for confirmation before applying an import.

After a confirmed import, applicable game data becomes part of the local Typekeeper save.

The original file you selected remains under your control at its existing location.

---

## 9) Recovery exports

If Typekeeper detects a save problem, it may allow you to export local recovery files.

Recovery exports can contain current, previous, or damaged save information.

These files are created only to help you preserve or recover local game progress.

Once exported, you control where those files are stored.

---

# Information Typekeeper does not collect

The current version of Typekeeper does not collect through the app:

- your name;
- email address;
- phone number;
- postal address;
- contacts;
- photos;
- camera data;
- microphone recordings;
- precise or approximate location;
- health information;
- financial-account information;
- advertising identifiers;
- browsing history;
- account credentials; or
- personal profiles for advertising.

Typekeeper does not operate an account system.

Typekeeper does not use Firebase, Google Gemini, OpenAI, advertising SDKs, analytics SDKs, CloudKit, Game Center, or a developer-operated gameplay server in the current release.

Typekeeper does not perform cross-app or cross-website tracking.

---

# Typing input

Typekeeper is a typing game and necessarily processes keyboard input locally so that the game can determine whether typed characters match the current gameplay challenge.

This input is processed as part of gameplay on your Mac.

Typekeeper does not transmit your gameplay keystrokes to FoxForge Studio or a third-party analytics service.

The game's local records store gameplay results and statistics rather than operating as a remote keystroke-logging service.

---

# Network and third parties

## 10) No gameplay-data server

The current version does not send your save file, progress, scores, typing statistics, wardrobe state, or settings to a FoxForge Studio server.

The game does not require an internet account to play.

---

## 11) Apple and macOS

Typekeeper relies on Apple-provided macOS technologies including:

- the application sandbox;
- WebKit;
- file-selection and file-sharing interfaces; and
- standard macOS application storage.

Apple may process information independently as part of operating macOS or the Mac App Store.

Apple's handling of such information is governed by Apple's own privacy policies.

Apple privacy information:

https://www.apple.com/legal/privacy/

---

## 12) Same or equal protection

Typekeeper does not currently share player data with third-party analytics, advertising, AI, or cloud-processing providers.

If a future version introduces a third party that processes user data for Typekeeper, that provider will be required to provide the **same or equal protection of user data** as stated in this policy and as required by Apple's App Review Guidelines.

This Privacy Policy will be updated if Typekeeper's data practices materially change.

---

# Data retention and deletion

## 13) Local game data

Typekeeper's save data remains locally on your Mac until it is deleted, reset, replaced, or removed through applicable macOS storage controls.

Typekeeper may retain a previous valid save and recovery copies locally to protect against accidental loss or save corruption.

Typekeeper does not maintain a server-side copy of this information.

---

## 14) Local records

Where the game provides a control to clear gameplay records, using that control removes the applicable local records from the active save.

Other progress, checkpoints, settings, wardrobe information, or recovery data may remain unless separately reset or removed.

---

## 15) Exported files

Save files or recovery files that you export remain wherever you chose to place them until you delete those files yourself.

Typekeeper cannot delete files that you exported to another folder, drive, backup system, cloud-storage service, email, messaging service, or other destination.

---

## 16) macOS backups

Local Typekeeper save information may be included in normal macOS or user-configured backups.

Copies retained by a backup system are controlled by that backup system and may remain after the current local copy is changed or deleted.

---

## 17) Server-side deletion

Typekeeper does not operate a Typekeeper account or server-side gameplay database in the current release.

Therefore, there is no FoxForge Studio Typekeeper account or cloud gameplay record that you need to request us to delete.

For questions about locating or removing local Typekeeper files, contact us using the address below.

---

# Security

Typekeeper uses Apple's application sandbox and local application storage.

Save files use integrity checks so that the game can detect unsupported, damaged, or incomplete save information.

Typekeeper also keeps a previous valid save where appropriate to reduce the risk of accidental progress loss.

No storage method can be guaranteed to be completely secure.

Exported JSON saves are ordinary files and should be stored only in locations you trust.

---

# Children’s privacy

Typekeeper does not require players to create an account or provide personal information.

Typekeeper does not knowingly collect personal information from children under 13 through a FoxForge Studio server.

---

# Changes to this policy

We may update this Privacy Policy if Typekeeper's features or data practices change.

The **Last updated** date above reflects the latest version.

---

# Contact

For privacy questions regarding Typekeeper: Path to the Crown, contact:

**FoxForge Studio**

**Email:** Simon.Yam227@gmail.com
