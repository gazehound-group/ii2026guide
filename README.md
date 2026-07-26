# 2026 ASFA International Invitational — Unofficial Entrant's Guide

A single-page, mobile-friendly guide to the **48th ASFA International Invitational** — Saturday 24 & Sunday 25 October 2026, Couch Ranch, Vinita, Oklahoma.

It reorganizes the official ASFA premium list into seven tabbed sections — event info, stakes, entries & fees, fields & judges, awards & trophies, trip planning, and forms & links — plus a cost estimator that runs entirely in your browser.

## Disclaimer

**This is an independent, unofficial guide created and maintained by lure coursing enthusiasts. It is not authorized, approved, or endorsed by the American Sighthound Field Association (ASFA), and the official ASFA premium always governs.**

The International Invitational is an ASFA-sanctioned event; the official premium list and entry materials are published by ASFA at [asfa.org](https://www.asfa.org). Where anything here disagrees with official ASFA rules, forms, or publications, **the official ASFA materials govern**. The full disclaimer is in the footer of the page itself.

## What's in this repo

| File | Purpose |
| --- | --- |
| `index.html` | The entire guide — self-contained markup, styles, and scripts |
| `hero-field.jpg` | Hero banner photograph (see [License](#license) — not covered by the MIT license) |
| `favicon.ico` | Browser tab icon — 16, 32, and 48 px packed into one file |
| `favicon-16x16.png`, `favicon-32x32.png` | PNG tab icons for browsers that prefer them |
| `apple-touch-icon.png` | 180 px icon for iOS home-screen bookmarks |
| `rabbit.png` | Rabbit mark for the "Results & Winners" teaser |
| `LICENSE` | MIT license for the site code, with third-party carve-outs |
| `README.md` | This file |

The icons are cropped from the Gazehound Group logo — the GG monogram with the running sighthound beneath it.

There is no build step, package manager, or framework. Tailwind CSS and Font Awesome load from CDNs; the Abel webfont loads from Google Fonts. Everything else is plain HTML, CSS, and vanilla JavaScript.

## Running it locally

Open `index.html` directly in a browser, or serve the folder so the hero image and fonts resolve cleanly:

```bash
python -m http.server 8137
# then visit http://localhost:8137/
```

## Accuracy and content sources

Every figure, date, and rule on the page was checked line by line against the official premium PDF (*2026 ASFA II Premium Final Final*, 18 pages) — fees, deadlines, stake definitions, veteran age minimums, judges, course lengths, field assignments, trophies, menus, and lodging all match the premium as published.

Two things worth knowing if you maintain this page:

- **It is a summary, not a reproduction.** Content is condensed and reorganized. The premium contains material not repeated here — complete entry forms, waivers, and full rules text. Always link people to the premium PDF for anything they must sign or submit.
- **A few items on the page are not in the premium** and were sourced elsewhere, so they need independent verification when they change: the New World Screwworm animal-health notice, street addresses and websites for the emergency vets and host motel, the official photographers' websites, and the `paypal.me/ASFACoursing` link.

Entry is presented as online-only by design. The premium still permits mail-in entry; the page points to the premium PDF for those instructions rather than restating an address.

## Reporting an error

Event details change, and a summary can drift from its source. If you spot something wrong or out of date, please [open an issue](https://github.com/gazehound-group/ii2026guide/issues/new) or email **info@gazehound.io**.

Please verify against the official premium first — if the two disagree, the premium is correct and this page needs fixing.

## License

The site code in this repository — the HTML, CSS, and JavaScript in `index.html` — is released under the [MIT License](LICENSE).

**Three things in and around this repository are not MIT-licensed:**

- **`hero-field.jpg`** is a photograph by **Peri Ann Taylor** ([periannphotography.artistwebsites.com](https://periannphotography.artistwebsites.com)). It is included here for use in this guide only. It is **not** covered by the MIT license and may not be reused, modified, redistributed, or sold on the basis of that license. Contact the photographer directly for any other use.
- **The event information** — schedules, fees, rules, stake definitions, and trophy listings — is drawn from ASFA's official premium list and remains the property of the **American Sighthound Field Association**. ASFA's name and marks are used descriptively to identify the event; this project is not affiliated with or endorsed by ASFA.
- **The icon files** (`favicon.ico`, `favicon-16x16.png`, `favicon-32x32.png`, `apple-touch-icon.png`) are cropped from the **Gazehound Group** logo, a brand mark of the project maintainer. They are included to identify this project. The MIT license covers the code, not rights to use the mark for other purposes.

## Credits

Built by lure coursing enthusiasts as a free community resource, with attention to recognized web accessibility standards (WCAG) so entrants can read event details comfortably from any device.

Hero photograph © Peri Ann Taylor. Event information © American Sighthound Field Association.
