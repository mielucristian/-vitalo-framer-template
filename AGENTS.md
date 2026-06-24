# AGENTS.md

Instructions for AI agents (Framer Agents, or external agents connected via MCP — Claude Code, Cursor, Codex, etc.) working on the **Vitalo** Framer project.

This file does not affect end users customizing the template manually. It exists to keep agent-driven edits consistent with the existing design system.

---

## Project context

Vitalo is a free Framer template for personal trainers and fitness coaches. It includes a 13-section homepage, a CMS-powered blog, contact page, FAQ, legal pages, and a 404 page.

Full structural documentation lives in:
- The **Documentation** design page inside this Framer project
- `README.md` in this repository

Read both before making structural changes.

---

## Design system — follow these conventions

**Typography**
- Headings use the `/Heading 1`, `/Heading 2`, `/Heading 3`, `/Name`, `/Price` text styles — all set to **Playfair Display**
- Body and UI text use `/Body`, `/Span`, `/Button`, `/Quote small` — all set to **Inter**
- Always apply text via existing text styles. Do not set fonts directly on individual text layers.

**Color**
- Use existing color styles (`/Dark 2`, `/Light 98`, `/Light 90`, `/White 100`, etc.) rather than hardcoded hex values
- If a new color is genuinely needed, create a new color style rather than a one-off fill

**Layout**
- Section containers use `48px` border radius on `/Light 98` or `/Dark 2` backgrounds, with consistent outer padding (`24px` on the section wrapper, `48–96px` inner padding on the content frame)
- Match this pattern for any new section rather than introducing a new container style

**Components**
- Reuse existing components (Button, Pricing Card, FAQ Tab, Blog Card, Transformation card, Newsletter card, Press article card, Ticker Text) instead of creating near-duplicate one-offs
- If a component needs a new state or variant, add it as a variant on the existing component rather than a separate component

---

## CMS collections

Six collections power this project: **Blog**, **Category**, **FAQs**, **Press**, **Legal**, **Transformations**.

- Do not rename existing field IDs — components are bound to them
- When adding CMS-driven content, populate items through the collection, not as hardcoded layers
- Programs & Pricing is intentionally **not** CMS-driven — it's a fixed, structural 3-tier layout. Do not migrate it to a collection unless explicitly asked.

---

## What agents should NOT do without being asked

- Do not delete or restructure the Documentation design page
- Do not remove or rename CMS fields that components reference
- Do not replace Playfair Display / Inter with other fonts as a "default improvement"
- Do not add tracking scripts, ads, or third-party embeds
- Do not change the license/usage terms stated in `README.md`

---

## Working with images

All current images are AI-generated or stock placeholders for demonstration only — not licensed for production use. Agents should treat any image-replacement task as expected and routine, not as something requiring a warning to the user each time.

---

## Support

For questions about intended structure or design decisions not covered here, the original author can be reached at **mielucristian@gmail.com**.
