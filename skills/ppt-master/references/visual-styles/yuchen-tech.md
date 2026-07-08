# Visual style: yuchen-tech

50/50 vertical photographic split with soft horizontal gradient transition glow, rounded rectangle card units, and refined full-width gradient page footers. Perfect for modern corporate tech slide decks, professional proposals, and product briefings.

---

## 1. Shape & decoration

- **Cover & Divider Layout**: 50/50 vertical split. Left side is clean white (or solid field), right side is a photographic tech scene.
- **Transition glow**: Overlay a white-to-transparent horizontal gradient mask (`white_gradient_mask.png`) on the left edge of the right-side photo to create a soft, seamless glow transition.
- **Content Containers**: Wrap content in rounded rectangle card shapes (fill white, border 0.5pt, adjustments `0.05` for 5% corner rounding).
- **Decorations**: Left-top page title decoration uses a horizontal gradient strip. Title underline is a horizontal gradient line. Avoid large flat solid color blocks.

## 2. Typography character

- Grotesque / Sans-serif neo-grotesque type stack (e.g., `Microsoft YaHei` for CJK, `Arial` for Latin/Numbers).
- Strong sizing contrast: Title (24pt Bold), Sub-headers (16pt-18pt Bold), Body text (14pt Regular), Labels (10pt-12pt).

## 3. Using the deck's colors

- **Primary colors**: Applied to titles, primary labels, and gradient highlights.
- **Bright accents**: Applied to active numbers, bullet icons, and category tags.
- **Footer bar**: Horizontal gradient strip running full width at the bottom (0.35 inches height), separated by a 1.5pt bright line on top.

## 4. Texture / elevation

- Restrained flat 2D planes, utilizing gradients for horizontal transitions and overlays rather than heavy drop shadows.

## 5. Paired image-rendering

`tech-scene` / `corporate-photo` — real-world, high-tech photographic assets (e.g. data centers, network devices, automation arms, monitor screens).

## 6. Illustration propensity

**supportive** — photographic background assets are essential for the cover and divider layouts. Spot illustrations on content pages are kept minimal and contained inside cards.

## 7. Presentation Composition Logic

- **Fixed Skeleton**: Every presentation must include a Cover Page (Slide 01), a TOC Page (Slide 02), and an Ending Q&A Page (last slide).
- **Flexible Body Section**: The presentation should be split into logical sections using Section Divider pages (过渡页/章节标题页). Body content pages are placed between their respective section dividers.
- **Flexible Visual Organization**: Use clean rounded cards (`rx` 12-16) or background panels to group structured items. For quantitative summaries, combine large metrics (Hero Numbers) with brief descriptions. Ensure comfortable whitespace margins and avoid filling cards with dense, unformatted walls of text.
