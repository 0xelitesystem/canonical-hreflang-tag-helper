# Canonical and Hreflang Tag Helper

This tool builds a canonical link tag and a set of hreflang alternate tags for the language and region versions of a page, plus an optional x-default. It outputs the block ready to paste into the head, and flags duplicate hreflang values.

**Live demo:** https://0xelitesystem.github.io/canonical-hreflang-tag-helper/

## What it does

Enter the canonical URL, then add a row for each language or region version with its hreflang code and URL, and an optional x-default. The tool assembles the canonical link and one alternate link per version, updating as you type, and warns if a hreflang value is repeated.

Put the block in the head of every version listed, and have each version reference all the others, including itself. Confirm each URL returns 200 and is itself canonical. This pairs with the canonical-and-hreflang reference.

## Aesthetic

A philatelic stamp album: an album page with each language version set in a perforated stamp, ink-and-cream tones, and the tag block printed below.

## Privacy

Everything runs in your browser. Nothing you type is sent anywhere, stored, or saved. Closing the tab clears it.

## Use it

Open `index.html` in any modern browser, or host it as a static page. No build step, no dependencies, no network calls.

## License

MIT. Copyright (c) 2026 0xelitesystem.
