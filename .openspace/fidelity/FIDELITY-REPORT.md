# Visual fidelity

Overall match: **31/100** — fonts, type sizes, spacing and each section measured in a browser on both sites, and how alike the pages look as pictures, each counted from what two unrelated pages score (0) to identical (100); the weaker of the two counts double, and so do the weakest page and device. How it's scored: docs/qa/import-fidelity.md.

**Next step:** The automatic move is rough (31/100): the words and pictures came across, but most of the design didn't. That's normal for custom-built sites. Claude can make it match closely: in Claude with the OpenSpace connector, use the finish-a-move prompt (or Studio's "Finish it with Claude"). It compares the old and new pages side by side and rebuilds what didn't come across, keeping every word and picture editable.

Scored two ways, side by side: **31/100 corrected**, 31/100 by the strict v3 scorer. The corrected score reads three things the strict one gets wrong (navigation in a header themed "brand", off-screen slides counted as columns, a picture-only band on a phone); the pages below list where it did.

Before auto-tuning: 25/100. What it changed:

- h2: 25.5px, 21px on phones
- section padding 192px
- section padding on phones 62px
- button corners sharp

Recreating low-scoring sections as custom components didn't raise the score (31/100), so none were kept.

## / at 1440px — 59/100

Checks passed: 100% · screenshots 76% alike (two unrelated pages compare at about 55%).

Original: https://thereforefilms.weebly.com/  
Imported: / (local preview)

| Check | Original | Imported | |
|---|---|---|---|

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | (no heading) | 100 | — |

## / at 390px — 68/100

Checks passed: 100% · screenshots 85% alike (two unrelated pages compare at about 65%).

Original: https://thereforefilms.weebly.com/  
Imported: / (local preview)

| Check | Original | Imported | |
|---|---|---|---|

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | (no heading) | 100 | — |

## /awards-etc-html at 1440px — 39/100

Checks passed: 56% · screenshots 75% alike (two unrelated pages compare at about 55%).

Original: https://thereforefilms.weebly.com/awards-etc.html/  
Imported: /awards-etc-html (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 2: present | Raleway 25.5px | not found | **differs** |
| Content width | 310px | 1280px | **differs** |
| Section padding | 244px | 192px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | NOMINATIONS / | 80 | Height: 2654px → 588px |

What would close the gap:

- choices.layout.contentWidth = 310

## /awards-etc-html at 390px — 38/100

Checks passed: 64% · screenshots 77% alike (two unrelated pages compare at about 65%).

Original: https://thereforefilms.weebly.com/awards-etc.html/  
Imported: /awards-etc-html (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 2: present | Raleway 21px | not found | **differs** |
| Buttons: present | Raleway 13.5px | not found | **differs** |
| Section padding | 182px | 60px | **differs** |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | NOMINATIONS / | 91 | Heading: Raleway 21px → Lora 21.1px |

What would close the gap:

- choices.layout.sectionPaddingMobile = 182

## /benjamin-html at 1440px — 28/100

Checks passed: 43% · screenshots 82% alike (two unrelated pages compare at about 55%).

Original: https://thereforefilms.weebly.com/benjamin.html/  
Imported: /benjamin-html (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 2: present | Raleway 25.5px | not found | **differs** |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | Benjamin's second film IT'S NO GAME | 49 | Heading: Raleway 25.5px → Lora 25.5px; Columns: 2 → 1; Height: 8404px → 2797px |

What would close the gap:

- Lay the text out in columns (a stack layout with more columns, or the text block's Columns style).

## /benjamin-html at 390px — 21/100

Checks passed: 72% · screenshots 68% alike (two unrelated pages compare at about 65%).

Original: https://thereforefilms.weebly.com/benjamin.html/  
Imported: /benjamin-html (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 2: present | Raleway 21px | not found | **differs** |
| Section padding | 38px | 60px | **differs** |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | (no heading) | 80 | Height: 222px → 459px |
| 2 | (no heading) | 80 | Height: 288px → 2795px |
| 3 | Benjamin's second film IT'S NO GAME | 77 | Heading: Raleway 21px → Lora 21.1px; Height: 545px → 2795px |
| 4 | SELECTED COVERAGE ​(for press or other enquires get in touch) | 77 | Heading: Raleway 21px → Lora 21.1px; Height: 9159px → 2795px |

What would close the gap:

- choices.layout.sectionPaddingMobile = 38

## /cinematographers-html at 1440px — 62/100

Checks passed: 75% · screenshots 83% alike (two unrelated pages compare at about 55%).

Original: https://thereforefilms.weebly.com/cinematographers.html/  
Imported: /cinematographers-html (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Section padding | 338px | 192px | **differs** |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | (no heading) | 100 | — |
| 2 | (no heading) | 67 | Image placement: left, 84% wide → none; Height: 62px → 715px |

What would close the gap:

- choices.layout.sectionPadding = 338
- Adjust the stack column spans (image column) or the image's side.

## /cinematographers-html at 390px — 72/100

Checks passed: 100% · screenshots 87% alike (two unrelated pages compare at about 65%).

Original: https://thereforefilms.weebly.com/cinematographers.html/  
Imported: /cinematographers-html (local preview)

| Check | Original | Imported | |
|---|---|---|---|

| # | Section | Match | Differences |
|---|---|---|---|

## /contact-html at 1440px — 36/100

Checks passed: 64% · screenshots 69% alike (two unrelated pages compare at about 55%).

Original: https://thereforefilms.weebly.com/contact.html/  
Imported: /contact-html (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading font | Raleway | Lora (close stand-in) | close (70%) |
| Heading 2 size | 25.5px | 25.5px | same |
| Label font | Raleway | Raleway | same |
| Buttons size | 14px | 15.6px | same |
| Buttons letter spacing and case | 0em, uppercase | 0.01em, uppercase | same |
| Section padding | 314px | 192px | **differs** |
| Button corners | 0px | 0px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | c o n t a c t | 29 | Heading: Oxygen 50px → Lora 25.5px; Columns: 2 → 1; Height: 1868px → 413px |

What would close the gap:

- Site Styles → choices.typography.heading = { family: "Raleway" } (Google Fonts), or upload it in Site Styles → Your fonts.
- choices.layout.sectionPadding = 314
- Lay the text out in columns (a stack layout with more columns, or the text block's Columns style).

## /contact-html at 390px — 49/100

Checks passed: 79% · screenshots 80% alike (two unrelated pages compare at about 65%).

Original: https://thereforefilms.weebly.com/contact.html/  
Imported: /contact-html (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading font | Raleway | Lora (close stand-in) | close (70%) |
| Heading 2 size | 21px | 21.1px | same |
| Label font | Raleway | Raleway | same |
| Buttons size | 14px | 14.6px | same |
| Buttons letter spacing and case | 0em, uppercase | 0.01em, uppercase | same |
| Section padding | 60px | 65.5px | same |
| Button corners | 0px | 0px | same |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | c o n t a c t | 57 | Heading: Oxygen 30px → Lora 21.1px; Height: 1878px → 156px |

What would close the gap:

- Site Styles → choices.typography.heading = { family: "Raleway" } (Google Fonts), or upload it in Site Styles → Your fonts.

## /films-by-benjamin-the-ai-html at 1440px — 20/100

Checks passed: 33% · screenshots 85% alike (two unrelated pages compare at about 55%).

Original: https://thereforefilms.weebly.com/films-by-benjamin-the-ai.html/  
Imported: /films-by-benjamin-the-ai-html (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 2: present | Raleway 25.5px | not found | **differs** |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | ​INTERVIEWS ​​Ars Technica ​Chicago Tribune Arte FiveThirtyEight Popular Science NPR - The Pulse Can | 40 | Columns: 3 → 1; Height: 9322px → 3894px |

What would close the gap:

- Lay the text out in columns (a stack layout with more columns, or the text block's Columns style).

## /films-by-benjamin-the-ai-html at 390px — 22/100

Checks passed: 67% · screenshots 69% alike (two unrelated pages compare at about 65%).

Original: https://thereforefilms.weebly.com/films-by-benjamin-the-ai.html/  
Imported: /films-by-benjamin-the-ai-html (local preview)

| Check | Original | Imported | |
|---|---|---|---|
| Heading 2: present | Raleway 21px | not found | **differs** |

| # | Section | Match | Differences |
|---|---|---|---|
| 1 | ​INTERVIEWS ​​Ars Technica ​Chicago Tribune Arte FiveThirtyEight Popular Science NPR - The Pulse Can | 80 | Height: 11672px → 3497px |

