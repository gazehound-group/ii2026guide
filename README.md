# 2026 ASFA International Invitational — Unofficial Entrant's Guide

A single-page, mobile-friendly guide to the **48th ASFA International Invitational** — Saturday 24 & Sunday 25 October 2026, Couch Ranch, Vinita, Oklahoma.

It reorganizes the official ASFA premium list into seven tabbed sections — event info, stakes, entries & fees, fields & judges, awards & trophies, plan your II trip, and resources — plus a cost estimator that runs entirely in your browser.

**This is an independent, unofficial guide created and maintained by lure coursing enthusiasts. It is not authorized, approved, or endorsed by the American Sighthound Field Association (ASFA), and the official ASFA premium always governs.** Where anything here disagrees with official ASFA rules, forms, or publications, the official ASFA materials govern. The full disclaimer is in the footer of the page itself.

## Layout

```
index.html     The entire guide — markup, styles, and scripts in one file
assets/        Hero photograph, favicons, and page artwork
favicon.ico    Copy of assets/favicon.ico, for clients that request /favicon.ico directly
```

There is no build step, package manager, or framework. Tailwind CSS and Font Awesome load from CDNs; the Abel webfont loads from Google Fonts. Everything else is plain HTML, CSS, and vanilla JavaScript.

## Accuracy and content sources

Every figure, date, and rule on the page was checked line by line against the official premium PDF (*2026 ASFA II Premium Final Final*, 18 pages) — fees, deadlines, stake definitions, veteran age minimums, judges, course lengths, field assignments, trophies, menus, and lodging all match the premium as published.

Two things worth knowing if you maintain this page:

- **It is a summary, not a reproduction.** Content is condensed and reorganized. The premium contains material not repeated here — complete entry forms, waivers, and full rules text. Always link people to the premium PDF for anything they must sign or submit.
- **A few items on the page are not in the premium** and were sourced elsewhere, so they need independent verification when they change: the New World Screwworm animal-health notice, street addresses and websites for the emergency vets and host motel, the official photographers' websites, and the `paypal.me/ASFACoursing` link.

Entry is presented as online-only by design. The premium still permits mail-in entry; the page points to the premium PDF for those instructions rather than restating an address.

## Reporting an error

Event details change, and a summary can drift from its source. If you spot something wrong or out of date, please [open an issue](https://github.com/jackrabbit-project/ii2026guide/issues/new) or email **info@gazehound.io**.

Please verify against the official premium first — if the two disagree, the premium is correct and this page needs fixing.

## License

The site code is released under the [MIT License](LICENSE). The hero photograph (© Peri Ann Taylor), the ASFA event information, and the Jackrabbit Project icon files are **not** MIT-licensed — see [LICENSE](LICENSE) for the carve-outs.
