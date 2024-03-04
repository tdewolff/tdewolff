# Taco de Wolff
https://dewolff.ai/

A collection of integrated tools and libraries using the Go programming language.
- [prompt](https://github.com/tdewolff/prompt): Command line prompting by scanning into any variable type using a text, select, or checkbox input prompt.
- [argp](https://github.com/tdewolff/argp): Command line argument parsing, including parsing lists and maps and configuration files.
- [font](https://github.com/tdewolff/font): Font parsing and manipulation for TTF, OTF, TTC, WOFF, WOFF2, and EOT file types.
  - [cmd/fontinfo](https://github.com/tdewolff/font/tree/master/cmd/fontinfo): Show font information and draw glyphs in terminal or as image.
  - [cmd/fontsubset](https://github.com/tdewolff/font/tree/master/cmd/fontsubset): Subset a font by selecting the given glyph IDs, glyph names, or literal characters.
- [locale](https://github.com/tdewolff/locale): Handling of locale-specific parsing of dates, date intervals, currencies, etc using the CLDR dataset.
- [mail](https://github.com/tdewolff/mail): Mail related utilities, including parsing DMARC and SMTP TLS reports and the milter protocol.
  - [milter](https://github.com/tdewolff/mail/tree/master/cmd/milter): A mail filter to prevent e-mail spoofing, use Sender Rewriting Scheme (SRS), and parse SMTP TLS/DMARC reports.
- [parse](https://github.com/tdewolff/parse): Parsing utilities with parsers for (mainly) web formats, such as HTML, CSS, JS, JSON, and XML.
- [minify](https://github.com/tdewolff/minify): High-performance minifiers for web file formats, such as HTML, CSS, JS, JSON, and XML.
  - [cmd/minify](https://github.com/tdewolff/minify/tree/master/cmd/minify): Command line tool to minify files.
- [canvas](https://github.com/tdewolff/canvas): Vector graphics library that can output raster images, SVGs, PDFs, HTML Canvas, TeX, PostScript, etc. file formats.
