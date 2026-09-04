# Beto Ruiz Alonso — Website Rebuild

## Project

New version of https://www.betoruizalonso.com/, a Berlin-based professional
photographer's portfolio site. Old site built on 22Slides.

Client: Beto Ruiz Alonso, portrait / fashion / event photographer, Berlin.

## Old site reference (for parity/content migration)

- Nav: Events, Portraits, Actors, About
- Services: portrait sessions, fashion photography, event documentation
- Featured work: TNW (The Next Web) Amsterdam conference coverage, 2018-2019
- Contact: info@betoruizalonso.com
- Social: Twitter, Instagram, LinkedIn, Flickr
- Design: clean/minimalist, large grid photo galleries, 2024 logo, cookie
  consent, copyright notices on images

## Stack (planned)

Astro (matches this workspace's other client/portfolio builds, e.g.
`astro-build/`, Swissfolio-style). Confirm before scaffolding — not yet
decided definitively.

## Notes

- Photo galleries are the dominant content type. Prioritize image
  performance (lazy load, responsive images, optimized formats) over
  anything else in the build.
- Preserve nav structure (Events / Portraits / Actors / About) unless client
  requests a change — it's proven IA for this kind of portfolio.

## Output Format

Per workspace convention: deliverables/reports as HTML, not markdown.
See `~/Claude/CLAUDE.md` for full workspace rules (caveman mode, no
em-dashes, artifact-copy rule, etc.) — those apply here too.
