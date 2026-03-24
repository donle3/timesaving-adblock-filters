# Time-saving Adblock Filters

Time-saving content filter lists for hiding specific contents of web-pages (with Brave, Vivaldi, uBlock Origin, Adblock, etc.).

This fork fixes some filters (e.g. Instagram homepage feed) from the original repo: https://github.com/liamperritt/timesaving-adblock-filters

## How to use in Brave or Vivaldi browser

Go to "Shields & privacy > Content filters" (Brave) or "Tracker and Ad Blocking > Manage Ad Blocking Sources" (Vivaldi) in the browser settings, and copy-paste the URL of the raw content of a list file from this repo (e.g. `https://raw.githubusercontent.com/liamperritt/timesaving-adblock-filters/refs/heads/main/lists/InstagramAntiDoomScrolling.txt`) into the "Add" URL text field, then click "Add/Import".

For use in the uBlock Origin or Adblock browser extensions for Firefox or Chrome/Chromium-based browsers, consult the relevant online documentation.

## Available filter lists

### Instagram Anti-Doom Scrolling

**Raw file URL:** https://raw.githubusercontent.com/donle3/timesaving-adblock-filters/refs/heads/main/lists/InstagramAntiDoomScrolling.txt

This list filters out all Instagram web app content that leads to endless doom scrolling, such as the Feed, Search and Reels, helping you stay connected while avoiding the time-wasting scrolling.

For best Instagram app experience on Android and Desktop:
1. In the Brave or Vivaldi browser, add the URL for this list as a "custom filter list" (see 'how-to' above)
2. Visit and log in to the Instagram website
3. In the browser options menu, select the "Add to home screen" option and install
4. Open the newly-installed Instagram PWA (Progressive Web App) from your homescreen and accept the prompt to enable notifications from Instagram
6. In Instagram "Notifications > Push Notifications" settings, turn off all push notifications except for "Messages from individual and group chats".

You'll now have a nicely-functioning version of the Instagram app that lets you stay connected with your friends without all the time-wasting content.

### Instagram Anti-Distractions

(Note: currently this list from the original repo is not fully functional)

**Raw file URL:** https://raw.githubusercontent.com/liamperritt/timesaving-adblock-filters/refs/heads/main/lists/InstagramAntiDistractions.txt

This list filters out Instagram web app content that most users find distracting, such as Notes, notification markers, pop-ups, clutter, etc.

Use in conjuction with the Instagram Anti-Doom Scrolling filter list for the most time-saving version of the Instagram web app. See the previous section's instructions on how to set up an Instagram PWA (Progressive Web App) for the best experience on Android and Desktop.


## Youtube

Installing Youtube as a PWA on mobile is a bit jank, since m.youtube.com can't be installed as a web app, but the desktop version can.

For mobile devices:
1. Visit Youtube in your browser
2. In the browser dropdown settings:
    1. Switch ON Desktop Site
    2. Add Page to Home Screen (should pop up option to install)
    3. Switch OFF Desktop Site (i.e. back to the mobile version of the site)

### Youtube Mobile Filters

**Raw file URL:** https://raw.githubusercontent.com/donle3/timesaving-adblock-filters/refs/heads/main/lists/YoutubeMobileFilters.txt

This list filters out algorithm-based scrolling feeds (home page, related videos under current video) and reduces appearances of shorts in the nav bar, search results, subscriptions, and history.
With this list only, you can still technically access shorts via a direct link or through a channel's shorts tab, but only the first video can be seen; subsequent videos are blacked out (though you can still hear them).
