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

- One `##` heading per question, phrased as the user would ask it.
- A general answer first, true across every platform.
- Then `###` sections **only where the platforms actually differ** — omit them
  when one answer covers everything, rather than writing three that repeat.
- Platform sections are named for what the user recognises: `iPad / macOS`,
  `Android`, `Web`.
