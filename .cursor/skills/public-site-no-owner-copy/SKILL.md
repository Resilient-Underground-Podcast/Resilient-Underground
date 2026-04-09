---
name: public-site-no-owner-copy
description: >-
  Keeps owner-only setup, activation, DNS, and backend instructions off public
  website copy. Use when writing or editing marketing pages, contact forms,
  footers, or any user-facing HTML/copy, or when the user mentions public vs
  owner-facing content for a live site.
---

# Public site: no owner-facing copy

## Rule

Content that exists only for the **site owner** (you)—activation links, FormSubmit or API setup steps, Google Workspace or MX routing, “check your inbox once,” deployment secrets, or similar—**must not** appear on the **live public site** (visible HTML, hero copy, form leads, footnotes visitors read).

## What to do instead

- Put that guidance in **private notes**, **README** (if the repo is not the visitor-facing surface), **issue trackers**, or tell the owner in chat—**not** in visitor-visible strings.
- **HTML comments** in shipped pages are still in the published file; avoid storing secrets there. Brief non-sensitive dev reminders are optional; prefer repo docs or local notes for owner steps.
- Public copy should read for **visitors**: what the feature does, what they should do, and (when needed) a short, reader-friendly note (e.g. “Your message is sent securely”).

## Quick check

Before shipping: ask whether each sentence is useful to a **first-time visitor**. If it only helps the person who runs the domain or the form backend, remove or relocate it.
