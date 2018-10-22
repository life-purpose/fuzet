# Soul Awakening

## Build

Tools:

* [Asciidoctor](https://asciidoctor.org/)
* [Asciidoctor PDF](https://asciidoctor.org/docs/asciidoctor-pdf/)

Publish:

1. `asciidoctor <NAME>.adoc`
2. copy `<NAME>.html` into branch: `master`
3. `asciidoctor-pdf <NAME>.adoc -a pdf-style=default-theme.yml -a pdf-fontsdir=<FONT_DIR> -o <NAME>.pdf`
4. copy `<NAME>.pdf` into branch: `master` / `downloads`
