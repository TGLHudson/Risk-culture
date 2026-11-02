# Hudson Risk Culture (HRC) website: working brief for Claude

This repository holds the Hudson Risk Culture website, served at **hudsonriskculture.com**, from T. G. L. Hudson. Read this file before doing any work here.

## The author

- T. G. L. Hudson works on operational risk, safety culture and barrier analysis, operating through Hudson Global Consulting from Cambridge, United Kingdom, and Leiden, The Netherlands. He has published some 25 conference papers and book chapters, most of them with the Society of Petroleum Engineers (SPE). Do not call them all peer-reviewed.
- His book *The Culture Ladder* is due from CRC Press in February 2027. It has its own site, thecultureladder.com, in the separate TCL-website repository. Further books will follow; the site lists them on its Books page. Keep the two sites distinct, but link between them.
- Consulting stance: "we're not working for management, we're working against the risk." The aim is management and workforce agreeing on how the risks being run are managed. The work is pro-worker and pro-union.
- Core belief: safety is not the opposite of dangerous work, it is the condition of being able to repeat it.

## Rules for this repository

1. **This repository is public.** Nothing confidential goes in: no client names or material, no tender documents, no unpublished papers or manuscript text, no private contact details.
2. **Voice.** Formal, precise, information-dense. No marketing padding, no hype words. Where the author's voice is unclear, flag it rather than inventing.
3. **Acronyms.** Spell out every acronym in full on first use on each page, including "Hudson Risk Culture (HRC)".
4. **Spelling.** British English.
5. **Claims.** Do not invent clients, case studies, testimonials, results or credentials. Leave a clearly marked placeholder instead.
6. **Title.** P. T. W. Hudson holds both a doctorate and a chair: call him Professor P. T. W. Hudson, then Professor Hudson.
7. **Provenance.** The safety culture ladder was developed by Professor P. T. W. Hudson, the author's father, from Ron Westrum's three organisational cultures (pathological, bureaucratic, generative); Westrum has not accepted the two added stages, so never imply he endorsed the five-stage ladder. Credit Westrum too. Credit him wherever the ladder's origin is described, and declare the relationship openly.

## Technical decisions

- Built with Jekyll, which GitHub Pages builds directly from this repository, for the custom domain hudsonriskculture.com. Pages are Markdown; the output is static HTML and CSS.
- Plain, fast, accessible pages that work without JavaScript and pass basic accessibility checks.
- Styling follows `STYLE.md`, the Hudson family style guide shared with hudsonglobalconsulting.com and thecultureladder.com. For this site, teal leads and gold is secondary. Agreed departure from `STYLE.md`: links inside running text stay underlined at rest, for accessibility.
- Fonts (Montserrat, Source Sans 3) are self-hosted in `assets/fonts/`.
- Where it does not conflict with this site's own identity, share the technical approach with TCL-website so both are maintained the same way.
- Do not change domain or DNS settings. Tim owns the domains. The README lists the DNS records to set at the registrar for go-live.

## Decisions made

- **Audience:** corporate clients first: operational, health, safety and environment leaders, and risk and governance functions. Trade unions and workforce representatives are secondary: the pro-worker, pro-union stance stays, but union content sits only in a section at the foot of Consulting, not on Home or Contact.
- **Pages:** Home, Approach, Consulting, Tools and licensing, Publications (with sub-pages for Professor P. T. W. Hudson and P. A. R. Hudson), Books, About, Contact.
- **Selling:** consulting and tool licensing are by enquiry only. No prices on the site.
- **Email:** enquiries@hudsonriskculture.com for consulting and licensing; info@hudsonriskculture.com for everything else. Role addresses only, never personal ones.
- **Intellectual property:** name a tool or method only once Tim has cleared it for public description; until then, a placeholder.
- **Publications:** list published work only, linked to the publisher's DOI or record. Never put copies of papers in this repository. Declare family relationships on each family member's page.

## Still open (ask before assuming)

- The hero photograph for the home page.
- One sentence stating P. A. R. Hudson's relationship to T. G. L. Hudson and to HRC.
- Whether later books get their own websites.
- Whether workforce participation is a condition of every engagement, or an aim.
