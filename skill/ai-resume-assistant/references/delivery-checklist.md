# Resume delivery checklist

Use this checklist for HTML and PDF production.

## Source synchronization

- Identify the active text source.
- Use matching basenames for Markdown, plain text, HTML, and PDF when all four are delivered.
- Compare major headings, dates, numbers, links, and project names across formats.
- Ensure the latest user correction appears everywhere.
- When the resume is intended for multiple hiring platforms, keep a plain-text version whose section order, dates, metrics, and links match the designed version.

## HTML

- Keep DOM order equal to intended reading order. Use semantic headings, sections, lists, and selectable text.
- Keep contact details readable without depending on icons.
- Use real `href` values for portfolio and project links; use `mailto:` and `tel:` when those links improve the requested digital deliverable.
- Provide print-specific CSS.
- Prefer a restrained layout that scans horizontally from top to bottom.
- Avoid decorative English labels that do not add information.
- Avoid tables, complex floats, and absolute positioning for the main reading flow. A visual date column may use a consistent CSS grid or flex pattern while preserving linear source order.
- Do not place essential text in images, pseudo-elements, headers, or footers. Use meaningful link text instead of long raw URLs when the destination permits it.

## Print CSS

- Set A4 page size and deliberate margins.
- Preserve intended colors with `print-color-adjust`.
- Replace browser-sensitive gradients with stable print colors when necessary.
- Control page breaks around headings, project blocks, and bullet groups.
- Avoid fixed heights that create bottom whitespace or clip content.
- Verify print preview or the rendered PDF; browser-screen fit is not evidence of page fit.

## PDF verification

- Confirm the PDF opens.
- Confirm expected page count.
- Render every page to images.
- Inspect the top, page breaks, links, accent rules, bottom balance, and avatar.
- Confirm text extraction is possible.
- Check that no glyphs, URLs, or bullets are clipped.

## Content integrity

- Do not shrink type below comfortable reading size simply to reach one page.
- Fix redundant wording and spacing before reducing font size.
- Do not delete evidence merely to create visual symmetry.
- Do not add unsupported text to fill whitespace.

## Page count and fit

- Use one A4 page when the requested market, role, and delivery brief favor a concise resume. Allow two or more pages when the user requests them or when seniority, publications, regulated experience, academic conventions, or material evidence would otherwise be distorted.
- Fit order when content overflows:
  1. compress redundant wording and hierarchy;
  2. reduce section, heading, and bullet spacing;
  3. tighten line height and letter spacing within comfortable bounds;
  4. only as a last resort reduce font size, and never below a comfortable reading size.
- Fit order when content is short of one page:
  1. expand line height and letter spacing within comfortable bounds;
  2. add section spacing and breathing room;
  3. never add filler text, decorative lines, or unsupported claims to fill the page.
- Do not delete evidence, compress meaning, or drop required contact details to reach one page.
- Re-render and inspect the PDF page count and bottom balance after any spacing change.

## Typography, color, and optional sections

- Choose a readable locale-appropriate font stack with fallbacks; do not require one operating-system font for every recipient.
- Set type size and line height from rendered readability, information density, and target medium. Treat template values as starting points, not release criteria.
- Use restrained, high-contrast color and verify grayscale and print output. If background color carries meaning, confirm it survives printing; preferably keep the hierarchy understandable without it.
- Align dates consistently across work, projects, and education when dates are displayed in a separate visual column. Give the date area enough width to avoid wrapping, but keep the source order linear.
- A photo, skills section, summary, or portfolio block is conditional on jurisdiction, target role, evidence value, user choice, and platform rules. Do not add or remove one by universal rule.

## Handoff

Provide absolute clickable links to:

1. active text source;
2. HTML;
3. PDF.

Mention page count and visual verification. Name any remaining difference explicitly.
