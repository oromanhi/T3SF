# Change Log
All notable changes to this project will be documented in this file.

## [1.0] - 2022-04-20 

Releasing the official public version of the framework!

### Added
- Added the proper project's documentation.
- Added a better and nicer README.
- Added contributing guidelines.
- Added platform-dependat files, such as `.env` `requirements.txt` and `bot.py`.
- Added support for more platforms: **WhatsApp** and **Telegram**!
- Added a To-Do list with ideas for next versions.
- Added the templates for issues and feature request.
- Added a few examples of the injects per platform as illustrative manner.
- New config file added as a way to configurate the framework.
- Framework added to PyPi for easier download.

### Changed
- Now the framework has a module for each platform's functions.
- There are new platform-wide handlers.


## [0.5] - 2022-04-03 [Private]

Now the framework supports Slack!

### Added
- Adding the Slack version of the bot.
  - Main features migrated.
  - Few functions exclusives to Slack created, such as format and inboxes fetcher.
- Adding a better way to separate Platforms with Folders.
- Adding a README with a How to for installation an a brief description of the bot and platforms.


## [0.4] - 2022-02-02 [Private]

Launching the latest _and better_ version of the framework supporting Discord! 

### Added
- Auto regex finder to match the categories' names
- Auto match with player's name from the MSEL.json and actual inbox's name
- Inbox now stored in a text file after getting the correct ones!
- New format for the injects! Now they have a profile picture for the sender

### Changed
-Now the start and resume function are merged into 1 process function!

### Fixed
- Fixed a bug within the resume function, injects not properly being choose!


## [0.3] - 2022-01-29 [Private]

Releasing a new feature for our unique platform, Discord, to add a new and better way to present injects

### Added
- Accepting new key from the JSON ("Photo") so we can attach a picture to the injects.
- Added exceptions handling for better debug.

### Remarkable tests
- Tested on education environment, with real case scenarios.


## [0.2] - 2021-12-13 [Private]

Releasing the second version, after many tests where new ideas emerged.

### Added
- New "Resume" function, to restart the bot in a certain Incident Id.
- New messages to inform the steps of the bots, such as remaining incidents, waiting time.
- New function to obtain automatically the channel's IDs [Discord].
 
### Changed
- Commented code.
- Code cleanup.

### Remarkable tests
- Tested on education environment, with real case scenarios.

 
## [0.1] - 2021-09-19 [Private]

Releasing the very first early version of the framework for internal testing.

### Added
- Basics functions suchs as framework's "start" and incidents handling.
- Adding Discord support. [Only platform].

### Special Thanks
Based on the We Learn Cybersecurity team idea (Matías Sliafertas, Gastón Ureta and Federico Pacheco)