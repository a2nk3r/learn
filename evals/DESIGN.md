---
name: "Mastering AI Evals: From Basics to Hands-On"
description: "A boxed-software reference manual opened at a tabbed division: a milk-acetate leaf over a full-hue Part board."
colors:
  sienna: "#8a3b1e"
  on-sienna: "#fbf7f2"
  oxide-orange: "#e0661f"
  on-oxide-orange: "#160c05"
  chrome-yellow: "#e8b50c"
  on-chrome-yellow: "#161204"
  grass: "#1a7f45"
  on-grass: "#f6fbf7"
  ultramarine: "#1f3fbf"
  on-ultramarine: "#f4f6ff"
  vermilion: "#c41d24"
  press-ink: "#171615"
  warm-graphite: "#44403b"
  hairline: "#1716152e"
  acetate-milk: "#f4f5f4"
  acetate-deep: "#e9eae8"
typography:
  display:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(3rem, 2rem + 4.2vw, 5.75rem)"
    fontWeight: 800
    lineHeight: 0.92
    letterSpacing: "-0.01em"
    fontVariation: "'wdth' 68"
  part-mark:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "5.5rem"
    fontWeight: 800
    lineHeight: 1
    fontVariation: "'wdth' 62"
  headline-division:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.875rem"
    fontWeight: 750
    lineHeight: 1.05
    fontVariation: "'wdth' 72"
  headline:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.375rem"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "0.01em"
    fontVariation: "'wdth' 72"
  title:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "1.125rem"
    fontWeight: 700
    letterSpacing: "0.02em"
    fontVariation: "'wdth' 80"
  dek:
    fontFamily: "EB Garamond, Iowan Old Style, Georgia, serif"
    fontSize: "1.4375rem"
    fontWeight: 400
    lineHeight: 1.45
  body:
    fontFamily: "EB Garamond, Iowan Old Style, Georgia, serif"
    fontSize: "1.25rem"
    fontWeight: 400
    lineHeight: 1.55
    fontFeature: "onum, pnum, kern"
  body-reference:
    fontFamily: "EB Garamond, Iowan Old Style, Georgia, serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.45
  caption:
    fontFamily: "EB Garamond, Iowan Old Style, Georgia, serif"
    fontSize: "1rem"
    fontWeight: 400
  label:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "0.875rem"
    fontWeight: 600
    letterSpacing: "0.06em"
    fontVariation: "'wdth' 75"
  label-tab:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 650
    letterSpacing: "0.08em"
    fontVariation: "'wdth' 75"
  mono-number:
    fontFamily: "JetBrains Mono, ui-monospace, SF Mono, Menlo, monospace"
    fontSize: "0.9375rem"
    fontWeight: 600
    letterSpacing: "0.02em"
  mono-label:
    fontFamily: "JetBrains Mono, ui-monospace, SF Mono, Menlo, monospace"
    fontSize: "0.8125rem"
    fontWeight: 600
  mono-listing:
    fontFamily: "JetBrains Mono, ui-monospace, SF Mono, Menlo, monospace"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.6
    fontFeature: "liga 0, calt 0"
  fold-summary:
    fontFamily: "Archivo, Helvetica Neue, Arial, sans-serif"
    fontSize: "1rem"
    fontWeight: 700
    letterSpacing: "0.04em"
    fontVariation: "'wdth' 80"
rounded:
  none: "0"
  key: "3px"
  row-tab: "0.375rem"
  tab: "0.5rem"
spacing:
  s1: "0.25rem"
  s2: "0.5rem"
  s3: "0.75rem"
  s4: "1rem"
  s5: "1.5rem"
  s6: "2rem"
  s7: "3rem"
  s8: "4.5rem"
  s9: "6rem"
  rail: "3.25rem"
  head-col: "12.5rem"
  measure: "62ch"
components:
  leaf:
    backgroundColor: "{colors.acetate-milk}"
    textColor: "{colors.press-ink}"
    rounded: "{rounded.none}"
    padding: "2rem 3rem 4.5rem 4.5rem"
    width: "76rem"
  part-mark:
    backgroundColor: "{colors.oxide-orange}"
    textColor: "{colors.on-oxide-orange}"
    typography: "{typography.part-mark}"
    rounded: "{rounded.none}"
    size: "7.5rem"
  running-head:
    textColor: "{colors.press-ink}"
    typography: "{typography.label}"
    padding: "0 0 0.75rem"
  rail-tab:
    backgroundColor: "{colors.sienna}"
    textColor: "{colors.on-sienna}"
    typography: "{typography.label-tab}"
    rounded: "{rounded.tab}"
    padding: "0.75rem 0.375rem 0.75rem 0"
  rail-tab-part1:
    backgroundColor: "{colors.oxide-orange}"
    textColor: "{colors.on-oxide-orange}"
  rail-tab-part2:
    backgroundColor: "{colors.chrome-yellow}"
    textColor: "{colors.on-chrome-yellow}"
  rail-tab-part3:
    backgroundColor: "{colors.grass}"
    textColor: "{colors.on-grass}"
  rail-tab-part4:
    backgroundColor: "{colors.ultramarine}"
    textColor: "{colors.on-ultramarine}"
  row-tab:
    backgroundColor: "{colors.oxide-orange}"
    textColor: "{colors.on-oxide-orange}"
    typography: "{typography.label-tab}"
    rounded: "{rounded.row-tab}"
    padding: "0.25rem 0.625rem 0.25rem 0.5rem"
  division-tab:
    backgroundColor: "{colors.oxide-orange}"
    textColor: "{colors.on-oxide-orange}"
    rounded: "{rounded.tab}"
    padding: "0.75rem 1rem"
  errata-slip:
    backgroundColor: "#ffffff"
    textColor: "{colors.press-ink}"
    rounded: "{rounded.none}"
    width: "48rem"
  errata-head:
    backgroundColor: "{colors.vermilion}"
    textColor: "#ffffff"
    typography: "{typography.title}"
    padding: "0.75rem 1.5rem"
  procedure-step-number:
    backgroundColor: "{colors.press-ink}"
    textColor: "{colors.acetate-milk}"
    rounded: "{rounded.none}"
    size: "2.25rem"
  where-marker:
    textColor: "{colors.press-ink}"
    typography: "{typography.mono-label}"
    rounded: "{rounded.none}"
    padding: "0.2rem 0.6rem"
  listing:
    backgroundColor: "#fbfbf9"
    textColor: "{colors.press-ink}"
    typography: "{typography.mono-listing}"
    rounded: "{rounded.none}"
    padding: "1rem"
    width: "56rem"
  listing-head:
    backgroundColor: "{colors.acetate-deep}"
    textColor: "{colors.warm-graphite}"
    typography: "{typography.mono-label}"
    padding: "0.5rem 1rem"
  inline-code:
    backgroundColor: "{colors.acetate-deep}"
    textColor: "{colors.press-ink}"
    rounded: "{rounded.key}"
    padding: "0.05em 0.3em"
  kbd:
    backgroundColor: "#ffffff"
    textColor: "{colors.press-ink}"
    rounded: "{rounded.key}"
    padding: "0.05em 0.4em"
  cite-marker-hover:
    backgroundColor: "{colors.press-ink}"
    textColor: "{colors.acetate-milk}"
    rounded: "2px"
  table-row-hover:
    backgroundColor: "{colors.acetate-deep}"
  fold-summary:
    textColor: "{colors.press-ink}"
    typography: "{typography.fold-summary}"
    padding: "0.75rem 0"
    width: "46rem"
  fold-meta:
    textColor: "{colors.warm-graphite}"
  fold-body:
    padding: "0 0 1rem 1.35rem"
  page-turn:
    textColor: "{colors.press-ink}"
    rounded: "{rounded.none}"
    padding: "0.75rem 1rem"
    width: "14rem"
  page-turn-hover:
    backgroundColor: "{colors.press-ink}"
    textColor: "{colors.acetate-milk}"
  page-turn-unwritten:
    textColor: "{colors.warm-graphite}"
---

# Design System: Mastering AI Evals

## Overview

**Creative North Star: "The Tabbed Reference Manual"**

Every page is a boxed-software manual lying open at one of its divisions. The page ground is that division's divider board, printed in one full hue with a fine paper grain; the reading matter sits on a milk-acetate leaf hinged over it, punched along its bound edge; a stepped rail of colored tabs runs down the fore edge so the reader can see the whole volume and where they are in it. The system is physical and literal: if a device would not exist in a printed, ring-bound manual (a glowing card, a floating action button, a run button), it does not exist here.

The voice is an engineer's reference, not a product site. Density is generous but disciplined: one long measure of serif text per section, heads hanging in a margin column, tables and figures allowed to run wide. Color is structural, never decorative: a hue tells you which Part you are in, and one reserved red tells you that a stated analogy is being corrected. The course explicitly refuses two looks: the docs-site sidebar with a link tree, and the dark AI-console page.

Everything ships as flat HTML files opened from disk. Fonts, the stylesheet, and figures are local; nothing on a page executes. Practice happens in VS Code and the terminal, and the components are built to send the reader there.

**Key Characteristics:**
- Full-hue Part board as the page ground, set once per page by `data-part` on `<body>`, with a fixed fractal-noise grain over it.
- Milk-acetate leaf, faintly tinted toward the board, with a crisp cut edge and three binder punches that show depth.
- Fore-edge tab rail: one tab per division, tab length proportional to the division's page count; the current tab extends and is punched.
- Three voices: condensed Archivo caps for structure, EB Garamond for prose, JetBrains Mono for machine text and numbering.
- Short, hard, down-right paper shadows; square sheets; rounded corners only on tabs and keycaps.
- One motion token: a 90ms two-step hinge, used only for state changes on interactive elements.
- Vermilion exists only on errata slips.

## Colors

A strategy of full-saturation division hues on a near-neutral acetate, with a single held-back red and a warm press-black for all text.

### Primary
The Part boards. Each is primary for its own division; only one is the page ground at a time.
- **Oxide Orange** (oxide-orange): Part 1, Foundations & Error Analysis. Ink on it is the near-black **on-oxide-orange** (5.6:1).
- **Chrome Yellow** (chrome-yellow): Part 2, Heuristic & Reference-Based Metrics. Ink: **on-chrome-yellow** (9.8:1).
- **Grass** (grass): Part 3, LLM-as-a-Judge. Ink: the pale **on-grass**. Measured at 4.82:1 after grass was darkened from #1f8a4c to #1a7f45 to clear 4.5:1 for the small caps it carries on tabs, row tabs, and figure labels.
- **Ultramarine** (ultramarine): Part 4, Golden Datasets, CI & Production. Ink: **on-ultramarine** (7.7:1).
- **Sienna** (sienna): the Contents division (`index.html`). Ink: **on-sienna** (7.2:1).

### Tertiary
- **Errata Vermilion** (vermilion): the head band and E-numbers of an errata slip, and its faint row rules (vermilion at 20% alpha). White on vermilion is 5.9:1.

### Neutral
- **Press Ink** (press-ink): all body text, heads, rules marked "strong", focus outlines, the procedure step squares, and the inverted page-turn hover.
- **Warm Graphite** (warm-graphite): secondary text only: glosses in tables, captions, the colophon, the "not yet written" state, the italic analogy line on the contents page, the listing head's language label, shell prompts and comments in listings, and the fold's open/close label.
- **Hairline** (hairline): press ink at 18% alpha, for row rules, section dividers, and dotted contents leaders.
- **Acetate Milk** (acetate-milk): the leaf base. In the build it is never used raw; it is mixed in OKLab with the current board (`color-mix(in oklab, #f4f5f4 96.5%, var(--board))`), so the leaf on Part 1 reads faintly warm and on Part 4 faintly cool.
- **Acetate Deep** (acetate-deep): the same mix at 94%; backs inline code, listing head rows, the `:target` highlight on a reference, and the hover tint on a ruled-table row.
- **Listing Paper** (#fbfbf9, component literal): the untinted near-white inside a listing's ink frame, so printed code reads as a separate sheet of the manual. Press ink on it is 17.4:1; warm graphite 9.9:1. There is no dark code ground in the system.

### Named Rules
**The Board Owns the Hue Rule.** A page's ground hue is chosen by exactly one attribute, `data-part` on `<body>` (`contents`, `1`, `2`, `3`, `4`), which sets `--board` and `--on-board`. Components that must show another Part's hue (rail tabs, row tabs, division tabs) take it from `data-tab`, never from a hardcoded color.

**The Errata-Only Vermilion Rule.** Vermilion appears on `.errata` and nowhere else: not for links, warnings, emphasis, or errors in listings. Its rarity is what makes a correction read as a correction.

**The Tinted Acetate Rule.** The leaf is never pure white and never a fixed gray; it always carries 3.5% of the board beneath it. Pure white is reserved for keycaps, the errata slip, and type on the vermilion band.

## Typography

**Display Font:** Archivo variable (with Helvetica Neue, Arial), width axis 62–125%, used condensed.
**Body Font:** EB Garamond variable, roman and italic (with Iowan Old Style, Georgia).
**Label/Mono Font:** JetBrains Mono variable (with ui-monospace, SF Mono, Menlo).

All three are bundled as woff2 subsets in `assets/fonts/` under the SIL Open Font License; there is no CDN fallback and none may be added.

**Character:** Condensed grotesque capitals do the manual's structural work, a book face carries the argument, and a code mono speaks wherever the machine or the cross-reference system speaks. Width is the main lever: the bigger the head, the narrower the cut.

### Hierarchy
- **Display** (800, clamp(3rem, 2rem + 4.2vw, 5.75rem), 0.92, width 68%, uppercase, balanced): the page title `h1`, one per page.
- **Part mark** (800, 5.5rem, 1, width 62%): the numeral or `§` in the board-colored square beside the title. 3.25rem below 820px.
- **Headline, division** (750, 1.875rem, 1.05, width 72%, uppercase): Part names on the contents page.
- **Headline** (700, 1.375rem, 1.1, width 72%, uppercase, balanced): section heads hanging in the margin column.
- **Title** (700, 1.125rem, width 80%, uppercase, 0.02em): sub-heads inside a section body, procedure step titles, the errata band (750, width 75%). Table terms and caption/figure labels use the same cut at 1.0625rem and inline size.
- **Dek** (400, 1.4375rem, 1.45): the standfirst under the title, capped at the measure. 1.25rem below 820px.
- **Body** (400, 1.25rem, 1.55, oldstyle proportional figures): running prose, capped at 62ch, `text-wrap: pretty`, hyphenated. 1.1875rem below 820px.
- **Body, reference** (400, 1.0625rem, 1.45–1.5): ruled tables and the reference list.
- **Caption** (400, 1rem, warm graphite): table captions and figure captions, led by a bold condensed-caps label ("Table 1.", "Figure 1.").
- **Label** (600, 0.875rem, 0.06em, width 75%, uppercase): running head and table column heads.
- **Label, tab** (650, 0.8125rem, 0.08em, width 75%, uppercase): rail tabs and row tabs.
- **Mono, number** (600, 0.9375rem): section numbers `1.1.x`. Mono at 0.75–0.875rem also sets folios, page numbers, reference numbers, citation markers (0.7em, raised), step counters, the spine label (0.6875rem, 0.14em caps), and the colophon.
- **Mono, listing** (400, 0.875rem, 1.6): code in listings; inline `code` is 0.8em on acetate deep, `kbd` 0.85em. Ligatures and contextual alternates are off in `code`, `kbd`, `samp`, `pre`, where markers, and folios, so `==`, `->`, and `!=` read as typed.
- **Fold summary** (700, 1rem, 0.04em, width 80%, uppercase): the summary line of a fold; inline code inside it keeps its own case and weight 500.

### Named Rules
**The Three Voices Rule.** Archivo condensed caps is the manual's structure (heads, tabs, labels, captions' lead words). EB Garamond is the author speaking. JetBrains Mono is the machine and the numbering system: commands, paths, keys, folios, section and reference numbers. A string never borrows another voice.

**The Width Axis Rule.** Condense heads with `font-stretch`, never with a different family: 62–68% for display, 70–72% for headlines and division tabs, 75% for labels and tabs, 78–80% for titles. Heads are uppercase; body text is never condensed.

**The Numbers Are Addresses Rule.** The mono number above a section head (`1.1.1`, `1.1.2`…) and the `p. 1.1` folio are a cross-reference system matched by anchor ids (`s-1-1-1`). They are not decoration. There are no eyebrow or kicker labels: no small category line above a title or head; the running head already says where you are.

## Layout

The page is a **volume**: the board fills the viewport; the leaf is centered with a max width of 76rem, padded 2rem top, 3rem fore edge, 4.5rem bottom and bound edge (the bound edge is wider to clear the punches). The volume reserves the rail width plus 2rem on the right so the leaf never slides under the tabs, and a mono spine label runs vertically up the board's left edge.

Inside the leaf, every major block is a two-column **hanging-head grid**: a 12.5rem margin column for the head and a fluid body column, 2rem apart. The title block (part mark | title + dek), each section (section head | body), the page turn, and each contents division (division tab | page list) share this grid, so their left edges align down the page. Body children are capped at the 62ch measure; `.wide` lets a table or figure run the full body column. Sections are separated by 4.5rem of space, not by rules; the title block and page turn carry the only full-width rules (1px hairline and 2px press ink, respectively; the running head also sits on a 2px press-ink rule).

The spacing scale is a nine-step rem ladder (s1 0.25rem to s9 6rem). Paragraphs are spaced by s4; heads within a body get s6 above and s2 below; component internals use s2–s5.

**Responsive.** At 1100px the margin column narrows to 9.5rem and the leaf padding tightens. At 820px the grid collapses to one column (heads stack above bodies), the spine label hides, the leaf gains a small board margin, body drops to 1.1875rem, and the tab rail turns horizontal: it becomes a sticky strip across the top with tabs hanging down from the top edge, words hidden, numbers kept. The running head drops the Part name (`.rh-desc`) and keeps course, Part number, and folio. On desktop, ruled tables keep a 52rem minimum width and scroll horizontally inside a focusable, labelled region; at 820px they restack: the caption moves above, the column heads become visually hidden, each row becomes a block between rules, and each cell is prefixed by its column name from `data-label` in small condensed caps. Every body `td` in a ruled table therefore carries `data-label`.

**Print.** The board turns white without grain, the rail, punches, spine label, and skip link disappear, the leaf prints as plain pages, and every fold prints expanded.

### Named Rules
**The Hanging Head Rule.** Heads live in the margin column and text lives in the body column. Do not center headings, do not put a head inside the text column at section level, and do not let prose exceed 62ch.

**The Flat Files Rule.** Every page is a flat HTML file at the project root (`index.html`, `part1-1-mental-model.html`, `part2-3-…html`) that references `assets/` relatively. Firefox's `file://` policy only lets a document load fonts from its own directory or below, so a page in a subfolder would lose its typefaces. No CDN, no build step, no network.

## Elevation & Depth

Depth is paper lying on paper. The board has tooth: a 240px tile of SVG `feTurbulence` fractal noise (base frequency 0.9, three octaves, black at roughly 30% opacity) fixed over its hue. Every sheet that would physically sit on top of another casts a short, hard shadow offset down and to the right (light from the upper left), with no spread and no glow. The leaf has a cut edge rather than a soft one: a 1px inset light line on its top and left and a 1px inset dark line on its bottom and right, with nothing bleeding past it. Shadows are static: nothing lifts on hover, and no surface floats above the leaf except the errata slip, which is literally tipped in. Inside the leaf everything is flat and separated by rules and space.

### Shadow Vocabulary
- **Leaf on board** (`box-shadow: inset 1px 1px 0 #ffffffb3, inset -1px -1px 0 #00000014, 3px 4px 6px #0000002e`): the acetate leaf; the two insets are its cut-edge highlight and shade.
- **Slip on leaf** (`box-shadow: 2px 4px 6px #00000033`): the errata slip, the only sheet tipped in at an angle. Listings are printed on the leaf and cast no shadow.
- **Mark on leaf** (`box-shadow: 2px 3px 4px #00000033` / `#00000030`): the part-mark square and contents division tabs.
- **Tab under leaf edge** (`box-shadow: -2px 2px 4px #00000038`): rail tabs, cast toward the leaf. On the horizontal mobile rail: `0 2px 3px #00000038` per tab and `0 2px 4px #00000026` under the strip.
- **Punched hole** (layered radial gradients): each of the three binder holes shows the board through the leaf, ringed by a thin dark rim (`#00000080`) and a light outer rim (`#ffffffe6`), with a dark crescent (`#000000a6` fading to `#00000040`) offset to the upper left inside the hole for depth. The current rail tab's hole is a solid ink dot with a faint inset highlight.

### Named Rules
**The Paper Stack Rule.** Only physical sheets cast shadows, offsets stay at or under 4px with blur at or under 6px, and shadow never signals state. State is shown by position (a tab slides out), outline, or inversion.

## Shapes

Sheets are square: the leaf, part mark, errata slip, listing, procedure step squares, "where" markers, and page-turn boxes all have hard 90° corners. The errata slip is the one sheet set off-axis: rotated -0.4deg from its top-left corner, with a perforated top edge of leaf-colored half-circles (0.75rem pitch). Rounding is reserved for things that are tabs, keys, or small inline marks. A rail tab rounds only its free edge (0.5rem on the leading corners, square where it tucks under the leaf); contents division tabs round their trailing corners by 0.5rem; row tabs by 0.375rem; keycaps and inline code by 3px; an inverted citation marker by 2px. Circles appear only as punches: the three binder holes on the leaf and the 0.625rem hole punched in the current tab.

Rules are the main line work: 3px press ink to open and close a ruled table, 1.5px under its column heads, 1px hairlines between rows, dotted hairlines as contents leaders, 1.5px press-ink boxes for page turns, "where" markers, and listings (page turns dashed when the target is unwritten), a 1.5px press-ink top rule over each fold. The fold's open/closed marker is a CSS border triangle. Gradients are used only to draw physical things: punches, the errata perforation, and the 135° hatching on face-down tabs; the board grain is an SVG noise filter.

### Named Rules
**The Tab Corner Rule.** A corner is rounded only if it is the free edge of a tab, a key, or a small inline mark (inline code, an inverted citation marker). Everything that is a sheet stays square.

## Components

### Tab rail (signature)
The volume's index, fixed to the fore edge. 3.25rem wide, full height, one tab per division in a vertical writing mode, colored by `data-tab` with its board ink. Each `li` sets `--extent` to the division's page count, so tab length shows how much is in each Part.
- **Default:** label-tab type, mono number above the word, 0.75rem padding, tucked under the leaf by the shadow.
- **Hover:** slides 0.375rem toward the reader via the hinge.
- **Current** (`aria-current="page"`): slides out 1rem, weight 800, a 2px inset press-ink outline, and a 0.625rem punched hole near the top. Does not move on hover.
- **Unwritten** (`aria-disabled="true"`, no `href`, `title="Part N is not written yet"`): face-down: 135° hairline hatching over the full hue (never desaturated, so the rail stays a legend for Table 1's row tabs), `not-allowed` cursor, no hover movement.
- **Mobile (≤820px):** a sticky horizontal strip; tabs hang from the top edge with bottom corners rounded, numbers only; current tab drops fully into view, others sit 0.75rem raised.
- **Contents tab:** at least 8.5rem tall on desktop; the current tab adds 1.75rem top padding so its punched hole clears the label.

### Running head
A flex row on a 2px press-ink rule: course title (linking home), Part, and Part name (`.rh-desc`, hidden at 820px and below) on the left in label caps; the mono folio (`p. 1.1`, `p. iii` for contents) on the right. Links show an underline only on hover.

### Title block
The hanging-head grid holding a 7.5rem board-colored part-mark square (numeral, or `§` for contents) beside the display title and dek; closed by a hairline.

### Section with hanging head
A `section` labelled by its `h2.section-head`, which holds a mono `.sec-num` on its own line above the condensed-caps head. The `.section-body` holds prose, sub-heads (title style), tables, figures, slips, and procedures.

### Ruled table
A manual's reference table, not a data grid. Caption below, led by "Table N."; head cells in label caps between a 3px and a 1.5px press-ink rule; rows on hairlines; closed by a 3px rule. Row-header cells stack a condensed-caps `.term` over a warm-graphite `.gloss`. Wrapped in `.table-wrap.wide` with `role="region"`, `aria-labelledby` pointing to the caption, and `tabindex="0"` for keyboard scrolling. On pointer devices wider than 820px a row tints to acetate deep under the pointer through the hinge. Body cells carry `data-label` with their column name for the stacked layout at 820px and below (see Layout).

### Row tab
An inline board-colored tab (`data-tab="1"`–`"4"`) that ties a table row to the Part teaching it; square on the left, 0.375rem round on the right.

### Figure plate
An inline SVG in `figure.plate.wide` (max 44rem) with `role="img"`, `<title>`, and a full `<desc>`; caption led by "Figure N.". SVG text uses Archivo at 75% width for labels and EB Garamond for gloss lines; fills use the Part hue that teaches each element, with that board's ink.

### Errata slip
An `aside.errata` tipped into the leaf: a white slip, max 48rem, rotated -0.4deg from its top-left corner, with a perforated top edge (leaf-colored half-circles via `::before`) and the slip shadow. A vermilion band holds the condensed-caps head in white. Items are an ordered list with mono vermilion counters `E1`, `E2`… hanging in the left margin, each led by a condensed bold claim, separated by 20%-vermilion rules. Use it only to correct a stated analogy or simplification.

### Procedure
The lab form: an `ol.procedure` whose counters are 2.25rem press-ink squares with mono numerals in acetate. Each step has a condensed-caps `.step-title`, then prose, `.where` markers, and listings. Steps are things the reader does in VS Code and the terminal.

### Where marker
A 1.5px press-ink box in mono that names the tool and the path to it (`` VS Code · View → Terminal · Ctrl + ` ``), with `kbd` keycaps. Spell modifier keys as words when the symbol would be too small to read (`Ctrl`, not ⌃). It names a place; it is never a button.

### Listing
Code for the reader to copy into a local file or type into a terminal. Printed in the manual's voice: a near-white panel (#fbfbf9, max 56rem, so a full script line fits beside the procedure counters) inside a 1.5px press-ink frame, no shadow. A mono head row on acetate deep carries the file path or "Terminal" in bold ink on the left and the language or shell on the right, over a 1px ink rule. Ligatures are off in all code so `==` and `->` read as typed. Shell prompts are a dim, unselectable `.prompt` span so copied text is clean; comments use `.comment`.

### Inline code and keys
Inline `code` sits on acetate deep with a 3px radius at 0.8em. `kbd` is a white keycap at 0.85em: 1px press-ink border, 2px bottom border, 3px radius, weight 600. Keycaps are not interactive and have no hover state.

### Citation marker and references
`.cite` is a raised mono `[n]` at 0.7em, joined to the preceding word with a word joiner (`&#8288;`) and given `aria-label="Reference n"`. The References section is a hanging-head section whose list puts a mono number in a 2.75rem column; the targeted entry highlights in acetate deep. On hover or focus a `.cite` marker inverts to acetate-on-ink through the hinge. The reference list sits inside an `open` `details.fold.fold-refs` so citation anchors always resolve.

### Page turn
Previous/next boxes in the body column under a 2px press-ink rule: 1.5px press-ink border, 14rem minimum width, condensed caps title under a mono direction line ("← Previous", "Next →"). Hover inverts to press ink on acetate via the hinge. An unwritten target is a `span` with `aria-disabled="true"`, dashed border, warm-graphite text, and "Next → not yet written".

### Fold
A `details.fold` for secondary material only: deeper dives, troubleshooting, expected output, full listings, references. Core theory, formulas, tables, and errata are never folded.
- **Summary:** condensed bold caps between a 1.5px press-ink top rule and a hairline bottom; a CSS triangle on the left that rotates 90° when open; a mono `.fold-meta` on the right reading "open" or "close". Inline `code` in a summary keeps its case. Hover underlines the summary at 2px.
- **Body:** indented 1.35rem under the triangle. On opening, the flap drops 0.5rem from its hinge line in the two-step hinge (`transform` only, so content is never hidden even if the animation never runs). Closing is instant.
- **Default state:** closed for optional material; `open` when other content links into it (references).
- **Print:** folds print expanded.

### Contents division
On `index.html`, each Part is a hanging-head row: a board-colored division tab (large condensed numeral plus small "Part") beside the Part name, the italic analogy line ("Heuristic evals ≈ unit tests"), and a page list with mono page numbers, titles (linked only when written), and a mono state ("written" / "not yet written") on dotted leaders.

### Equation
MathML only, no script: `div.equation` holds a `math[display="block"]` at 1.3rem and a mono `.eq-num` such as `(3)` on the right, between two hairlines, capped at the 62ch measure, and scrolls sideways if it is wider. Equations are numbered per Part, in reading order; a derived form takes a prime, such as `(1′)`. Math is set in the operating system's math font (STIX Two Math on macOS, then Latin Modern Math or Cambria Math), so nothing is downloaded. Every block `math` carries an `aria-label` that reads the formula in words. A `p.where-vars` directly below defines the symbols in warm graphite at 1.0625rem. Inline math sits in running text; `ln` is followed by a 0.1667em `mspace`, and short inline math that must not break is wrapped in a `nowrap` span.

### Planned, not yet built
- **Mock terminal:** a static display of a terminal session's output (for example a passing pytest run) is required by the Part 2 lab but does not exist. The listing is the nearest existing component; nothing is specified until it is built.

### Named Rules
**The No Run Button Rule.** Nothing on a page executes. There are no interactive widgets, run buttons, copy-to-run controls, calculators, or live consoles. Labs point to VS Code and the terminal through procedures, where markers, and listings.

**The Face-Down Rule.** A page that is not written yet is shown, not hidden: a hatched, full-hue `aria-disabled` rail tab; a dashed `aria-disabled` page turn; a "not yet written" state on the contents page. Never give an unwritten page an `href`.

**The Hinge Rule.** The system has one motion token: a 90ms `steps(2, jump-end)` hinge. It moves tabs on `transform`, drops an opening fold on `transform`, rotates the fold triangle, snaps the page-turn and citation inversions, thickens link underlines on hover, and tints a ruled-table row under the pointer (pointer devices, desktop width only). Nothing fades, eases, or animates layout, nothing moves on scroll or page load, and `prefers-reduced-motion` removes every transition and animation.

## Do's and Don'ts

### Do:
- **Do** set `data-part` on `<body>` for every page (`contents`, `1`–`4`) and let it choose the board; use `data-tab` on any component that shows another Part's hue.
- **Do** put every page at the project root as a flat file and reference `assets/css/course.css` relatively; keep fonts in `assets/fonts/`.
- **Do** number sections `P.p.n` (`1.1.1`) with a mono `.sec-num` and matching anchor ids, and match the folio in the running head to the page number.
- **Do** keep the hanging-head grid: a 12.5rem margin column for heads, body text at 62ch, `.wide` only for tables and figures.
- **Do** list every unwritten page as a face-down `aria-disabled` tab or turn without an `href`.
- **Do** send labs to VS Code and the terminal with `.procedure`, `.where`, and `.listing`, and label each listing with its file path or "Terminal".
- **Do** caption tables and figures as "Table N." / "Figure N." in condensed bold caps, and give every SVG figure a `<title>` and full `<desc>`.
- **Do** use only the 90ms two-step hinge for motion, and only to show a state change on an interactive element.
- **Do** put deeper dives, troubleshooting, and references in a `details.fold`; keep core theory unfolded.

### Don't:
- **Don't** use vermilion outside `.errata`.
- **Don't** make the page, the leaf, or a listing dark; the dark AI-console look is rejected.
- **Don't** add a docs-site sidebar or link tree; navigation is the tab rail, the running head, the contents page, and the page turn.
- **Don't** add eyebrow or kicker labels above titles or heads; section numbers and the running head already locate the reader.
- **Don't** add run buttons, interactive widgets, code runners, or in-browser evaluation.
- **Don't** load fonts, scripts, or styles from a CDN, or put pages in subfolders.
- **Don't** round sheets, cards, or panels; only tabs, keycaps, and inline code are rounded.
- **Don't** use shadows for hover or state, or any shadow larger than the paper-stack offsets.
- **Don't** use fades, easing curves, or layout animation.
