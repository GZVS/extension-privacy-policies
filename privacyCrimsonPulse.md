# Crimson Pulse Privacy Policy

**Effective date:** 2 November 2026
**Applies to:** Crimson Pulse — YouTube Visualizer, version 0.4.0 and later
**Developer:** GZVS (Georgios Zacharidis)
**Contact:** gzvsDev@icloud.com
**Web version:** https://gzvs.github.io/crimson-pulse/privacy.html

## Purpose

Crimson Pulse displays music-reactive visualizations on YouTube and YouTube Music. Audio processing happens on your device after you explicitly start a session.

## Information processed on your device

- Tab audio: Crimson Pulse accesses audio from the selected supported tab and calculates frequency and energy measurements in memory. It does not use your microphone, capture screen video, or create audio recordings.
- Current tab and website content: the tab identifier, current page URL, player elements, and playback state are used to check compatibility, position the visualizer, and manage the session. The extension does not create a browsing-history database.
- Now playing caption: while the visuals are showing, the extension reads the title (and, on YouTube Music, the artist) of the current track from the page to display it on screen. This text is used only for that display; it is not saved or sent anywhere. You can turn the caption off in the settings.
- Page interaction: pointer, click, scroll, touch, and keyboard events reset the inactivity timer and hide the visualization. Event histories and typed text are not stored. Configured extension shortcuts control the active session.
- Preferences and presets: visual settings, separate YouTube and YouTube Music settings, favorite styles, and custom preset names and settings are saved in local extension storage. These settings are not synced by the extension or uploaded to the developer.

## Use and sharing

This information is used only to provide the visualization and its controls. Captured audio is connected back to your audio output so you can continue hearing the video. Crimson Pulse has no developer backend, analytics, advertising system, account system, or remote executable code. The extension does not sell data or send audio, page activity, or settings to the developer or other recipients. Data is not used for credit or lending decisions.

## Retention and deletion

Audio buffers, frequency data, tab identifiers, and inactivity timing are transient. Preferences remain in the browser profile until changed or the extension is uninstalled. Delete a custom preset using the Delete button after selecting it. Uninstalling the extension removes its local extension settings from that browser profile.

## Session controls

Use Stop visualizer to end audio capture. Closing the captured tab or navigating away from supported watch pages stops the session. Navigation between supported watch pages may keep the session active. A reload or browser interruption may require starting again. The show/hide shortcut changes visualization visibility; it does not stop audio capture. Press Esc to leave fullscreen.

## Permissions

- storage: save visual preferences and custom presets locally.
- activeTab: identify and authorize the tab selected when you invoke the extension.
- tabCapture: access that tab's audio after you start a session.
- offscreen: analyze the audio and preserve playback while the popup is closed.
- scripting: when you start Crimson Pulse on a YouTube or YouTube Music tab that was open before the extension was installed or updated, add the visualizer to that tab so it works without a reload.
- Content scripts on www.youtube.com and music.youtube.com: access the player, playback state, and interaction events needed to display and dismiss visuals.

## Donations and external services

The optional support button opens PayPal at https://paypal.me/Zacharidis. PayPal's policies apply to that website and any payment. Crimson Pulse does not process payment details. The developer may receive donor information directly from PayPal under its service terms. YouTube, Microsoft Edge, and other browsers operate under their own privacy policies.

## Changes and contact

This policy will be updated when the extension's data practices change. For privacy questions or support, contact gzvsDev@icloud.com.
