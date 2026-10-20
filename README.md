# Redaction Carousel Maker

Write a post as plain text and get 1080 x 1350 carousel slides in the ben.j.ads look: paper ground, condensed lowercase headlines, a lime highlighter for the conclusion and a redaction bar with a lime tab for the sheisty beat.

Open `index.html` in any browser. No build step and no dependencies.

- **Slide types:** cover, point, figure (a bar chart, one bar can be the hero), conclusion and signoff.
- **Markup:** `*words*` puts a lime highlighter behind the words, `[[words]]` hides them behind a redaction bar with a lime tab. The tool warns when a slide has more than one highlight.
- **Controls:** your handle, paper or olive ground, and an optional "made with ben.j.ads" mark on the sign-off.
- **Export:** a PNG per slide, or all of them at once. Nothing is uploaded.

A browser port of the carousel generator in the ben.j.ads design system, using the same layout rules, font metrics and markup. Replace the placeholder numbers in the sample figure: never publish invented data.

## License

Code is MIT licensed ([LICENSE](LICENSE)). The bundled fonts (Bricolage Grotesque, Archivo) are SIL OFL 1.1, with licenses in `fonts/`. The ben.j.ads wordmark and footnote mark in `logo/` are Ben Johnston's brand assets and are not covered by the MIT license.
