# JLPT N1 Grammar

The files in this directory show the [HTML][]/[Stencil][]/[Javascript][] and [CSS][] code I
used to create my [Japanese Language Proficiency Test][] (JLPT) Level N1
**Grammar** flash cards using [Anki][].

The files are here to serve as a reference to anyone that cannot or does not
want to use the `JLPT N1 Grammar.apkg` [Anki Packaged Deck][] file included at
the root level of this repository.

You will have a much easier time just importing the packaged deck than
re-creating this deck from scratch, so I recommend doing so if you are able to.

## Fields

In order for the code to work, the following named fields must exist in the
deck:

1. Example
2. Grammar Pattern
3. Grammar Pattern Meaning
4. Examples
5. Grammar Notes

![Grammar Fields][]

All the fields used the default options aside from the following fields:

- Grammar Pattern: enabled "Sort by this field in the browser" radio button
- Examples: checked "Remember last input when adding"
- Grammar Notes: checked "Remember last input when adding"

## Cards

Each of the files in this directory corresponds to a radio button-ed part of
the Template section of the Card Type for the Anki Deck (which can be accessed
via the `[Cards...]` button in the Fields screenshot above):

- `front-template.html` -> Front Template
- `back-template.html` -> Back Template
- `styling.css` -> Styling

### Front Template

![Grammar Front Template][]

### Back Template

![Grammar Back Template][]

### Styling

![Grammar Styling][]

[Anki]: https://apps.ankiweb.net/
[Anki Packaged Deck]: https://apps.ankiweb.net/docs/manual20.html#exporting-packaged-decks
[CSS]: https://en.wikipedia.org/wiki/CSS
[Grammar Back Template]: ../../assets/grammar-back-template.jpg
[Grammar Fields]: ../../assets/grammar-fields.jpg
[Grammar Front Template]: ../../assets/grammar-front-template.jpg
[Grammar Styling]: ../../assets/grammar-styling.jpg
[HTML]: https://en.wikipedia.org/wiki/HTML
[Japanese Language Proficiency Test]: https://www.jlpt.jp/e/
[Javascript]: https://developer.mozilla.org/en-US/docs/Web/JavaScript
[Stencil]: https://stencil.fuller.li/en/latest/
