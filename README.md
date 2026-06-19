# Vitalo — Personal Trainer Framer Template

**Free** · Built in Framer · [Live Preview](https://vitalo.framer.website)

A premium-feeling, free Framer template for personal trainers and fitness coaches. Includes a full homepage with 13 sections, a CMS-powered blog, contact page, FAQ, legal pages, and a 404 page.

Built with **Playfair Display** for headings and **Inter** for body text, on a dark editorial color palette.

---

## Getting started

1. Open the [live preview](https://vitalo.framer.website)
2. Duplicate / remix the project into your own Framer account
3. Replace the placeholder content and images with your own
4. Publish

A full **Documentation** design page is included inside the Framer project itself — open it on the canvas for in-context guidance as you customize.

---

## Pages

| Page | Path | Description |
|---|---|---|
| Home | `/` | Main landing page with all 13 sections |
| Blog | `/blog` | Index of all articles, pulled from the Blog CMS collection |
| Blog post | `/blog/:slug` | Individual article template |
| Contact | `/contact` | Contact page with the message form |
| Legal | `/legal/:slug` | Privacy, Cookie, Terms, and Refund policies, pulled from the Legal CMS collection |
| 404 | `/404` | Not found page |

---

## Homepage sections

1. **Hero** — name, headline, intro, and primary CTA
2. **Stats** — key numbers (clients, countries, hours coached)
3. **About** — trainer story and personal stats
4. **Social Proof** — client testimonial slider
5. **Transformation Gallery** — client results, powered by the Transformations CMS collection
6. **How it Works** — 4-step process explainer
7. **Programs & Pricing** — 3 program tiers (hardcoded, not CMS)
8. **Featured In / Press** — publication mentions, powered by the Press CMS collection
9. **FAQ** — common questions, powered by the FAQs CMS collection
10. **Final CTA Banner** — closing call to action with OrbReveal animation
11. **Blog preview** — latest articles, powered by the Blog CMS collection
12. **Ticker** — scrolling strip of stats and quotes
13. **Footer** — navigation, legal links, newsletter card, contact info

---

## CMS collections

<details>
<summary><b>Blog</b></summary>
<br>

- Title
- Slug
- Status (Draft / Published)
- Publish date
- Meta description
- Categories *(multi-reference → Category collection)*
- Excerpt
- Content *(rich text)*
</details>

<details>
<summary><b>Category</b></summary>
<br>

- Name
- Referenced by Blog posts to enable filtering
</details>

<details>
<summary><b>FAQs</b></summary>
<br>

- Question
- Answer
</details>

<details>
<summary><b>Press</b></summary>
<br>

- Publication
- Date
- Title
- Pull quote
- Image
</details>

<details>
<summary><b>Legal</b></summary>
<br>

- Title
- Slug
- Effective date
- Intro
- Body *(rich text)*
</details>

<details>
<summary><b>Transformations</b></summary>
<br>

- Name
- Age
- Program *(Starter / Transform / Elite)*
- Result
- Duration
- Quote
- Photo *(after photo only)*
</details>

---

## Key components

| Component | Purpose |
|---|---|
| Button / Button Form | Primary and secondary CTAs; form variant includes loading, success, and error states |
| Pricing Card | Used in the Programs & Pricing section |
| FAQ Tab | Expandable question/answer accordion item |
| Press article card | Default and hover states, used in Featured In |
| Blog Card | Article preview card |
| Transformation card | Client result card |
| Newsletter card | Footer subscribe form |
| Ticker Text | Scrolling marquee text item |
| OrbReveal *(code component)* | Scroll-driven expanding circle animation with adjustable padding, colors, and timing |

---

## Typography

- **Headings** — Playfair Display, used in `/Heading 1`, `/Heading 2`, `/Heading 3`, `/Name`, `/Price`
- **Body & UI** — Inter, used in `/Body`, `/Span`, `/Button`, `/Quote small`

To change fonts globally, update the text styles in the Framer Style panel rather than editing individual text layers.

---

## Customization guide

**Images**
Replace all placeholder photos with your own. AI-generated and stock photos used in this demo are not licensed for resale or production use.

**Colors**
Edit the color styles listed in the Style panel (e.g. `/Dark 2`, `/Light 98`) to update the palette across the whole site.

**CMS content**
Open the CMS panel, select a collection, and edit or add items directly. No design changes needed.

**Contact form**
Connect the Message form to your email provider or automation tool of choice via the Framer Form settings.

**Pricing**
Programs & Pricing cards are hardcoded by design — pricing tiers are a structural decision, not repeating content. Duplicate a card and edit it directly to add or change tiers.

---

## License

Free to use, customize, and remix for personal or commercial projects. Attribution is appreciated but not required.

---

## Support

Questions about customizing Vitalo? Reach out at **mielucristian@gmail.com** and you'll get a reply within 24 hours.
