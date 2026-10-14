# Zenith Guard Privacy Policy

**Effective date:** 14 October 2026
**Applies to:** Zenith Guard browser extension, version 3.2.0 and later
**Developer:** GZVS (Georgios Zacharidis)
**Contact:** zsgeorgios@icloud.com

## Summary

Zenith Guard does not collect, store on any server, sell or share any personal data. Everything the extension does happens inside your browser. The developer has no servers, analytics or telemetry, and never receives any information about you or your browsing.

## What Zenith Guard does

Zenith Guard blocks ads, trackers, tracking parameters and known dangerous websites. You can also turn on optional adult-site and gambling-site blocking. It does this with filter rules packaged inside the extension, which Chrome's built-in Declarative Net Request engine applies. Packaged CSS hides empty ad placeholders. On youtube.com, a packaged script removes ad entries from the video player's data and skips video ads.

## Information processed on your device

To work, the extension has to process some information locally. None of it ever leaves your device:

- **Web addresses and requests.** Chrome compares the requests your browser makes against Zenith Guard's bundled rules. The extension doesn't receive or log these requests, and it keeps no history of the sites you visit or the requests it blocks.
- **Page hostname.** On each page, the cleanup script reads the site's hostname in memory, only to check whether you've added that site to your allowed websites.
- **YouTube player data.** On youtube.com, a script edits the video player's data in the page's memory to remove ad entries. It doesn't read, store or send your viewing history, account details or any other content.

Zenith Guard doesn't read form fields, passwords, messages or the text of the pages you visit.

## Information stored on your device

Zenith Guard stores the following in your browser profile, using Chrome's extension storage:

- Your filter settings (which shields are on or off)
- The list of websites you've chosen to allow
- Whether the filters were applied successfully
- Temporarily, the result of the "Test blocking" check if you run it. This is cleared when the browser closes.

None of this is synced to your Google account or sent to the developer or anyone else. Your settings are shared between normal and Incognito windows in the same profile. They're deleted when you remove the extension.

## Data sharing and selling

Zenith Guard has no backend, analytics, advertising SDK, crash reporting or automatic filter-list downloads. It doesn't transmit, sell, rent or share any user data, and it doesn't use data for advertising, profiling or creditworthiness. Filter lists are updated only through new versions of the extension published on the Chrome Web Store.

## Permissions

| Permission | Why it's needed |
|---|---|
| `declarativeNetRequest` | Applies the packaged block, redirect and allow rules inside Chrome |
| `storage` | Saves your settings and allowed websites locally |
| `sidePanel` | Shows Zenith Guard's controls in Chrome's side panel |
| `scripting` | Manages the extension's own packaged content scripts |
| Access to all websites | Blocks and redirects on any site you visit and hides ad placeholders. The YouTube script runs only on youtube.com |

## External links

The popup and settings page contain a link to the developer's GitHub profile (https://github.com/GZVS) and an optional donation link (https://www.paypal.com/paypalme/Zacharidis). These links open only when you click them, and they send no referrer or other data from the extension. Once you're on those sites, their own privacy policies apply.

## Children

Zenith Guard doesn't collect personal information from anyone, including children under 13.

## Your choices

You can pause all protection, turn any filter off, add or remove allowed websites, or uninstall the extension at any time. Uninstalling removes all data the extension stored.

## Changes to this policy

If this policy changes, the updated version will be published at this address with a new effective date. If Zenith Guard ever starts handling data differently, it will ask for your consent first.

## Contact

Questions about this policy: **zsgeorgios@icloud.com**
