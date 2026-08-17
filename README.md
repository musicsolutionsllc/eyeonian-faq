# EyeOnian™ Frequently Asked Questions

Source for the GitHub Pages site at
<https://musicsolutionsllc.github.io/eyeonian-faq/>

**This repo is the source of truth for this document.** Edit it here, by hand,
through the GitHub web UI — that is the intended workflow and it needs no local
toolchain.

## Layout

| Path | Purpose |
|---|---|
| `index.md` | **The document.** Linked from the FAQ link on eyeonian.com. |
| `_config.yml` | Site title and description. The title renders as the page heading. |

## Not versioned, on purpose

Unlike the Privacy Policy, EULA and Release Notes, this document carries **no
version and no "last updated" line**, keeps no `vN.N/` directories and no
archive, and is **not vendored into any app build**. Those documents are pinned
because an app ships a frozen copy of the exact text a user accepted; the FAQ is
a web page that describes how the apps behave. It can be corrected at any time
without an app release, and nothing needs to agree with a hash.

## House style

This is a LIST of questions, so each entry has to read as one entry — not as a
page of its own. An answer that runs half a screen stops looking like an item in
a list.

- The page heading comes from `_config.yml` via the theme, exactly as on the
  privacy and EULA sites. Do **not** write an `#` heading in `index.md`: it
  renders as body text rather than the site heading and no longer matches them.
- One `##` heading per question, phrased as the user would ask it. `##` is the
  largest heading any entry uses.
- A short answer first, true across every platform.
- Where platforms differ, put the differences in **bullets inside that answer** —
  not in subheadings, which make one question look like three. Bold the platform
  name and keep each to a sentence or two: `iPad / macOS`, `Android`, `Web`.
- Omit the bullets entirely when one answer covers every platform.
