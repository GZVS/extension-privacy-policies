# Spartan Shield Privacy Policy

**Effective date:** 24 October 2026
**Applies to:** Spartan Shield browser extension (formerly Spartan Shield), version 5.0.0 and later
**Developer:** GZVS (Georgios Zacharidis)
**Contact:** zsgeorgios@icloud.com

## Summary

Spartan Shield does not collect, store on any server, sell or share any personal data. Everything the extension does happens inside your browser. The developer has no servers, analytics or telemetry, and never receives any information about you or your browsing.

## What Spartan Shield does

Spartan Shield blocks ads, trackers, tracking parameters, social media widgets, cookie-consent pop-ups and known dangerous websites. You can also turn on optional adult-site and gambling-site blocking. It does this with filter rules packaged inside the extension, which Chrome's built-in Declarative Net Request engine applies. Packaged CSS hides empty ad placeholders. On youtube.com, a packaged script removes ad entries from the video player's data and skips video ads.

Its safety features warn you about fake websites and unsafe password pages. They also stop pages from secretly copying commands to your clipboard or asking to send notifications, skip tracking redirect links, and send websites the Global Privacy Control signal. They spot tech-support scam pages that try to trap you, and ask you to double-check the address the first time you sign in to a new site.

## Information processed on your device

To work, the extension has to process some information locally. None of it ever leaves your device:

- **Web addresses and requests.** Chrome compares the requests your browser makes against Spartan Shield's bundled rules. The extension doesn't receive or log these requests, and it keeps no history of the sites you visit or the requests it blocks.
- **Page hostname.** On each page, the cleanup script reads the site's hostname in memory, only to check whether you've added that site to your allowed websites.
- **YouTube player data.** On youtube.com, a script edits the video player's data in the page's memory to remove ad entries. It doesn't read, store or send your viewing history, account details or any other content.

- **Website address checks.** The fake-site check compares the address of the page you're on with a list of well-known brands bundled in the extension. The password check notes whether a page has a password field and whether the page uses HTTPS. Neither check reads what you type.
- **Text a page tries to copy.** When a website tries to put text on your clipboard, Spartan Shield checks that text in memory for hidden commands (like PowerShell or Terminal commands). If it finds one, it stops the copy and shows you the command. Spartan Shield never reads your clipboard, and never stores or sends what it checked.
- **Notification requests.** When a website asks to show notifications, Spartan Shield declines on your behalf unless you've allowed that site.
- **Scam page behaviour.** To spot tech-support scam pages, Spartan Shield notices when a page forces fullscreen, locks your keyboard or mouse, repeats pop-up dialogs or plays sound, and checks the page's visible text in memory for scare phrases like "virus detected, call support". Nothing about the page is stored or sent.
- **Password fields for the first sign-in check.** When you click into a password field, Spartan Shield checks whether you've signed in to that site before. It never reads what you type.
- **Tracking redirect links.** When you open a link like `l.facebook.com/l.php?u=…` or `google.com/url?q=…`, Spartan Shield reads the real address from the link and opens it directly, so the tracking step is skipped.

Spartan Shield doesn't read what you type into forms, your passwords, messages, clipboard contents or the text of the pages you visit.

## Information stored on your device

Spartan Shield stores the following in your browser profile, using Chrome's extension storage:

- Your filter settings (which shields are on or off)
- The list of websites you've chosen to allow, the sites you've let ask for notifications, and the sites you've told it not to warn about
- Whether the filters were applied successfully
- A count of scams and dangerous sites stopped, shown in the popup. No addresses are kept.
- For the first sign-in check: scrambled fingerprints (one-way hashes) of the sites you sign in to. They can't be turned back into addresses, and you can clear them in Settings with "Forget them".
- Temporarily, the result of the "Test blocking" check if you run it, and any dangerous site you chose to open with "Proceed anyway". Both are cleared when the browser closes.

None of this is synced to your Google account or sent to the developer or anyone else. Your settings are shared between normal and Incognito windows in the same profile. They're deleted when you remove the extension.

## Signals sent to websites

When "Do-not-sell signal (GPC)" is on, your browser sends websites the standard `Sec-GPC: 1` header, and pages can read `navigator.globalPrivacyControl = true`. This signal contains no information about you. It tells the site you don't want your data sold or shared, and websites have to honour it under several privacy laws.

## Data sharing and selling

Spartan Shield has no backend, analytics, advertising SDK, crash reporting or automatic filter-list downloads. It doesn't transmit, sell, rent or share any user data, and it doesn't use data for advertising, profiling or creditworthiness. Filter lists are updated only through new versions of the extension published on the Chrome Web Store.

## Permissions

| Permission | Why it's needed |
|---|---|
| `declarativeNetRequest` | Applies the packaged block, redirect and allow rules inside Chrome |
| `storage` | Saves your settings and allowed websites locally |
| `sidePanel` | Shows Spartan Shield's controls in Chrome's side panel |
| `scripting` | Turns the packaged YouTube ad-cleaner and the safety guards (clipboard, scam pages, notifications, privacy signal) on and off to match your settings |
| Access to all websites | Blocks and redirects on any site you visit, hides ad placeholders and shows safety warnings. The YouTube script runs only on youtube.com |

## External links

The popup and settings page contain a link to the developer's GitHub profile (https://github.com/GZVS) and an optional donation link (https://www.paypal.com/paypalme/Zacharidis). These links open only when you click them, and they send no referrer or other data from the extension. Once you're on those sites, their own privacy policies apply.

## Children

Spartan Shield doesn't collect personal information from anyone, including children under 13.

## Your choices

You can pause all protection, turn any filter off, add or remove allowed websites, or uninstall the extension at any time. Uninstalling removes all data the extension stored.

## Changes to this policy

If this policy changes, the updated version will be published at this address with a new effective date. If Spartan Shield ever starts handling data differently, it will ask for your consent first.

## Contact

Questions about this policy: **zsgeorgios@icloud.com**
