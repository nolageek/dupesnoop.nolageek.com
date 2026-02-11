---
layout: page
title: What's New
include_in_header: true
---
## Version 2026.02.11
### Changes
- Added "Reprise" tag to song listing, if the song contains (reprise).
- Added new Topbar Menu to Library view, and added new option to Catalog Search view:  Added option to expand full song/track information to make it easy to find unwanted versions.
- Added "Date" tag to song listing when expanded. Note that this uses Apple's metadata for album release dates and when it comes to Re-Releases and Anniversary Editions it is NOT reliable. I am working on a solution for showing proper release dates as well as a means to find the "original" versions of songs.
- Using ISRC (International Standard Recording Code) to track literal Exact duplicates of songs that are included in multiple releaes in a shady attempt to get you to re-save them to your library. (Looking at you, "ABCDEFU" with your 10+ identical versions on multiple "my setlist from that show where I opened for someone" album releases. Love the song, but FU2.) 
	- ISRC (International Standard Recording Code) is a unique, 12-character digital fingerprint for a specific sound or music video recording, used globally to track its usage, sales, and streams, ensuring correct royalty collection for artists, labels, and publishers across digital platforms and physical releases. Each ISRC identifies a particular recording, not the underlying composition, meaning remixes, covers, or different versions of a song each get a unique code.

### Bug Fixes
- A few small bugs squashed.

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
