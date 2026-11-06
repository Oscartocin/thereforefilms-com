# Import report: Therefore Films

Imported from https://thereforefilms.weebly.com (WordPress) on 2026-11-06 with `openspace import wordpress`.
Sources: page HTML, the sitemap. 242 requests.

## Summary

- **26** pages, **0** collection items in 0 collection(s)
- **197** media files (8.3 MB) downloaded into `media/`
- **25** redirects so old addresses keep working
- **53** item(s) need your attention (below)

## Pages

| Old address | OpenSpace | Title | Sections | Blocks |
| --- | --- | --- | ---: | ---: |
| `/` | `/` | Home | 3 | 11 |
| `/sign-language.html` | `/sign-language-html` | Sign Language | 3 | 5 |
| `/contact.html` | `/contact-html` | Contact | 7 | 11 |
| `/films-by-benjamin-the-ai.html` | `/films-by-benjamin-the-ai-html` | Films by Benjamin the A.I. | 3 | 11 |
| `/poster--behind-the-scenes.html` | `/poster-behind-the-scenes-html` | Poster & Behind the Scenes | 3 | 191 |
| `/awards-etc.html` | `/awards-etc-html` | Awards etc. | 3 | 9 |
| `/cinematographers.html` | `/cinematographers-html` | Cinematographers | 3 | 3 |
| `/industry-screener.html` | `/industry-screener-html` | Industry Screener | 3 | 5 |
| `/benjamin.html` | `/benjamin-html` | Benjamin | 3 | 9 |
| `/oscar.html` | `/oscar-html` | Oscar | 3 | 9 |
| `/press.html` | `/press-html` | Press | 3 | 3 |
| `/teaching.html` | `/teaching-html` | Teaching | 5 | 6 |
| `/interviews.html` | `/interviews-html` | Interviews | 11 | 11 |
| `/press--quotes.html` | `/press-quotes-html` | Press & Quotes | 3 | 12 |
| `/films.html` | `/films-html` | Films by Oscar Sharp | 5 | 5 |
| `/works-in-progress.html` | `/works-in-progress-html` | Works in Progress | 3 | 7 |
| `/sunspring.html` | `/sunspring-html` | Sunspring | 3 | 9 |
| `/the-kaacutermaacuten-line.html` | `/the-kaacutermaacuten-line-html` | The Kármán Line | 3 | 8 |
| `/forna.html` | `/forna-html` | Forna | 3 | 5 |
| `/youtube.html` | `/youtube-html` | YouTube | 3 | 5 |
| `/sketchbook.html` | `/sketchbook-html` | Sketchbook | 7 | 49 |
| `/links.html` | `/links-html` | Links | 3 | 3 |
| `/therefore-friends.html` | `/therefore-friends-html` | Therefore Friends | 3 | 3 |
| `/watch-films.html` | `/watch-films-html` | Films by Oscar Sharp | 5 | 5 |
| `/newsletter.html` | `/newsletter-html` | Newsletter | 1 | 2 |
| `/oscar-sharp.html` | `/oscar-sharp-html` | Oscar Sharp | 3 | 8 |

## Design

The look was recreated with OpenSpace's own design system (Site Styles tokens, section color themes, layouts and section presets), not by copying WordPress's CSS or code.

- Brand color #dea227 (the site's accent color).
- Fonts on WordPress: Lora / Raleway → pairing "Lora & Inter" (Lora / Inter), same family for Lora. Licensed fonts can be uploaded in Site Styles → Fonts.
- Fonts on WordPress kept as they are (Lora, Raleway): free on Google Fonts, self-hosted with the site.
- The contrast solver adjusted 3 color pairing(s) so every section theme meets WCAG AA (e.g. light accent, light accent-hover).
- Page background #f9f9f9 on WordPress → #fafafa (text contrast 15.6:1).

Design check: 0 error(s), 215 warning(s).

- warning (/): “Home” has no clear call to action — nothing tells visitors what to do next.
- warning (/sign-language-html): “Sign Language” has no clear call to action — nothing tells visitors what to do next.
- warning (/contact-html): Four sections in a row use the light color theme, so the page reads as one long block.
- warning (/films-by-benjamin-the-ai-html): “Films by Benjamin the A.I.” has no clear call to action — nothing tells visitors what to do next.
- warning (/poster-behind-the-scenes-html): An image in this image block has no alt text, so people using screen readers won't know what it shows.
- warning (/poster-behind-the-scenes-html): An image in this image block has no alt text, so people using screen readers won't know what it shows.
- warning (/poster-behind-the-scenes-html): An image in this image block has no alt text, so people using screen readers won't know what it shows.
- warning (/poster-behind-the-scenes-html): An image in this image block has no alt text, so people using screen readers won't know what it shows.
- warning (/poster-behind-the-scenes-html): An image in this image block has no alt text, so people using screen readers won't know what it shows.
- warning (/poster-behind-the-scenes-html): An image in this image block has no alt text, so people using screen readers won't know what it shows.
- warning (/poster-behind-the-scenes-html): An image in this image block has no alt text, so people using screen readers won't know what it shows.
- warning (/poster-behind-the-scenes-html): An image in this image block has no alt text, so people using screen readers won't know what it shows.
- … and 203 more: run Design check in Studio or `design_check` with Claude.

## Needs attention

### Custom code and embeds

- Site-wide scripts were found (4: cdn2.editmysite.com, cdn11.editmysite.com, player.vimeo.com, platform.twitter.com). They were **not** copied: add what you still need (analytics, chat) in Settings → Advanced. WordPress-specific scripts won't work here. _(site)_
- Embed moved into a sandboxed Embed block. Check it still works. _(/films-by-benjamin-the-ai.html, /industry-screener.html, /benjamin.html, /press--quotes.html, +3 more)_

### Blocks that need a look

- A 2-column table with 1 rows doesn't fit OpenSpace's table block (up to 6 columns, 40 rows, short cells); it was kept as text, one line per row. _(/, /films-by-benjamin-the-ai.html, /awards-etc.html, /benjamin.html, +5 more)_
- A 4-column table with 1 rows doesn't fit OpenSpace's table block (up to 6 columns, 40 rows, short cells); it was kept as text, one line per row. _(/contact.html, /press--quotes.html)_
- A 3-column table with 1 rows doesn't fit OpenSpace's table block (up to 6 columns, 40 rows, short cells); it was kept as text, one line per row. _(/films-by-benjamin-the-ai.html, /awards-etc.html)_
- A 3-column table with 5 rows doesn't fit OpenSpace's table block (up to 6 columns, 40 rows, short cells); it was kept as text, one line per row. _(/newsletter.html)_

### Links

- Text link to /cdn-cgi/l/email-protection led to a page that wasn't imported; the link was removed. _(/contact.html)_
- Text link to /shhhhhh.html led to a page that wasn't imported; the link was removed. _(/links.html, /therefore-friends.html)_

### Pages that couldn't be read

- The WordPress REST API isn't public on this site, so pages and posts were read from their HTML. Pass the WordPress export (Tools → Export) with --export for complete content. _(/wp-json/)_

### Other

- The page had no Heading 1; its first heading was made the Heading 1 (search engines and screen readers use it). _(/contact.html, /poster--behind-the-scenes.html, /awards-etc.html, /benjamin.html, +10 more)_

## Redirects

Saved in `content/site.json` (`redirects`), published with the site:

| From | To |
| --- | --- |
| `/sign-language.html` | `/sign-language-html/` |
| `/contact.html` | `/contact-html/` |
| `/films-by-benjamin-the-ai.html` | `/films-by-benjamin-the-ai-html/` |
| `/poster--behind-the-scenes.html` | `/poster-behind-the-scenes-html/` |
| `/awards-etc.html` | `/awards-etc-html/` |
| `/cinematographers.html` | `/cinematographers-html/` |
| `/industry-screener.html` | `/industry-screener-html/` |
| `/benjamin.html` | `/benjamin-html/` |
| `/oscar.html` | `/oscar-html/` |
| `/press.html` | `/press-html/` |
| `/teaching.html` | `/teaching-html/` |
| `/interviews.html` | `/interviews-html/` |
| `/press--quotes.html` | `/press-quotes-html/` |
| `/films.html` | `/films-html/` |
| `/works-in-progress.html` | `/works-in-progress-html/` |
| `/sunspring.html` | `/sunspring-html/` |
| `/the-kaacutermaacuten-line.html` | `/the-kaacutermaacuten-line-html/` |
| `/forna.html` | `/forna-html/` |
| `/youtube.html` | `/youtube-html/` |
| `/sketchbook.html` | `/sketchbook-html/` |
| `/links.html` | `/links-html/` |
| `/therefore-friends.html` | `/therefore-friends-html/` |
| `/watch-films.html` | `/watch-films-html/` |
| `/newsletter.html` | `/newsletter-html/` |
| `/oscar-sharp.html` | `/oscar-sharp-html/` |

## Not moved by the importer

- Plugins and what they do: WooCommerce orders and customers, booking, membership, LMS and form plugins (their pages are imported as content; the functionality needs an OpenSpace block or a service).
- Comments, users and their roles, and custom post types other than pages and posts.
- Shortcodes and page-builder widgets without an OpenSpace equivalent (listed above).
- Draft and private content unless you pass the WordPress export (WXR) with `--export`.
- Form submissions, newsletter subscribers, member accounts and comments.
- Analytics and SEO history (search engines follow the redirects).

## Next steps

1. `npm install`, then `npx openspace check` (it should report no errors) and `npx openspace dev` to look around.
2. Bring it to visual parity with Claude: in this folder run `claude`, then `/openspace:migrate https://thereforefilms.weebly.com` (or ask Claude to compare each page with the original). It screenshots both sites at desktop and mobile and adjusts presets, Site Styles and sections — never raw HTML.
3. Fix the items under **Needs attention**, then publish (push to GitHub, or `publish` with Claude).
4. Move the domain only after the new site is live and checked:
   - add the custom domain in OpenSpace (`deploy.customDomain` in `openspace.json`, or the Hub);
   - at your DNS provider (your registrar or elsewhere), point the records at the new host as the domain guide says (GitHub Pages: `A`/`CNAME` records; Cloudflare: the Pages project's records);
   - keep the WordPress hosting until the new site serves your domain over HTTPS and the redirects work; then cancel it (and transfer the domain if you like).

