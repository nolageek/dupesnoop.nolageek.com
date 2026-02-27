---
layout: page
title: What's New
include_in_header: true
---
## Version 2026.02.28
### Changes
- Added an alert when you reach the 50-track maximum in the queue. This prevents stalling situations that could cause issues. I'll likely make this a user-configurable option (100?).
- Added new track tags to the song row view: Remix, Demo, Musical.
- Changed the release year tag to always display.
- Made all metadata tags from Apple white on dark grey to differentiate them from programmatically created tags. This is also the start of a system to calculate accurate release dates.
-  Updated the display of the Favorite, Search, and Queue buttons in the Song Detail view.
- Reworked the Onboarding tutorial to avoid confusion.

----

### Bug Fixes
- Fixed issue with how "Edition" tags are determined.
- Other visual and performance tweaks.

----

## Version 2026.02.16
### Changes
- Added "Reprise" tag to songs that contain a reprise version.
- Added a new top menu bar to the Library view and a new option to the Catalog Search view for expanding full song/track information, making it easier to identify unwanted versions.
- Added "Date" tag to expanded song listings. Note that this uses Apple's metadata for album release dates, which is unreliable for re-releases and anniversary editions. I'm working on a solution to display proper release dates and identify original versions of songs.
- Added "Exact" tag to song listings that match other songs identically in both Library and Catalog Search views. When a song has multiple versions with exact matches, the tags display in different colors to distinguish between them.
- Dramatically improved performance when scrolling through the Library tab.
- Groups with tracks already in the DupeSnoop playlist are hidden by default. You can show them using the option in the Library tab's top menu.
- Implemented ISRC tracking to detect literal duplicates of songs included across multiple releases in what appears to be an attempt to get you to re-save them. (I'm looking at you, "ABCDEFU" with your 10+ identical versions across multiple "My Setlist from That Show Where I Opened for Someone" album releases. Great song, but seriously?)
#### What is ISRC?
- **ISRC (International Standard Recording Code)** is a unique, 12-character digital fingerprint for a specific sound or music video recording, used globally to track its usage, sales, and streams, ensuring correct royalty collection for artists, labels, and publishers across digital platforms and physical releases. Each ISRC identifies a particular recording, not the underlying composition, meaning remixes, covers, or different versions of a song each get a unique code.

----

### Bug Fixes
- A few small bugs squashed.
- Loading screens no longer show the navigation bar too early.
- Pull-To-Refresh now properly udpates DupeSnoop playlist membership.

----

## Version 2026.01.24
### Changes
- Added tags under songs in library to make it easier to see if Deluxe, Soundtrack, Compilation, etc..
- Added iCloud storage for Hidden Group storage, to avoid losing your hidden group data.

### Bug Fixes
- Fixed bug where the 0.99 subscription for 1 month wasn't showing.
- Fixed bug where Full Title wasn't showing when long pressing a song in the library.

----

## Version 2026.01.17
### Bug Fixes
- Fixed bug with Onboarding Tutorial showing code instead of star. (5525)
- Fixed bug when using popovers to show messages in Queue. Switched to using alerts. (5525)
- Also switched to using alerts instead of popovers elsewhere, for consistancy. (5525)
- Added option to create empty playlist when tapping Open Queue when one didn't exist. (5525)

----

## Version 2025.12.23
### Changes
- About page: Redesigned Contact section with NavigationLink-style rows
- About page: Added "Send Feedback" with in-app email composer
- About page: Replaced tip options with link to Deluxe Special Edition subscription
- Theme system: Added forceDarkMode parameter for per-theme dark mode control
- Theme system: Navigation bar titles now use theme's headerColor
- Theme system: Added app-wide themed accent color support

### Bug Fixes
- Premium themes now properly require subscription to select

---

## Version 2025.12.11
### Changes
- Alternate app icons (for Special Deluxe Edition)
- Alternate logo images
- What's New page added to Settings
- Settings page: Added Support section
- Settings page: Added subscriptions to Deluxe Special Edition options
- Settings page: Moved Manage Hidden Groups to main settings page
- DupeSnoop theme use dark mode regardless of system setting

### Bug Fixes
- Replaced "Below" with "Above" in Onboarding Tutorial
- Fixed some issues with gradients on splash screen
- Fixed header formatting on CatalogSearchView
- Tweaked spacing between Filter and Sort pickers

----

## Version 2025.12.5
### Changes
- Added first In-App Purchase (.99 Tip option)
- Added Unfavorite All, and Queue All to Duplicate group header row.
- Tweaked UI

### Bug Fixes
- Fixed status toggles in CatalogSearchView

---

## Version 2025.11.29
- First semi-public TestFlight release
