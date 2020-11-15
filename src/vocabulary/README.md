# JLPT N1 Vocabulary

The files in this directory show the [HTML][]/[Stencil][] and [CSS][] code I
used to create my [Japanese Language Proficiency Test][] (JLPT) Level N1
**Vocabulary** flash cards using [Anki][].

The files are here to serve as a reference to anyone that cannot or does not
want to use the `JLPT N1 Vocabulary.apkg` [Anki Packaged Deck][] file included
at the root level of this repository.

You will have a much easier time just importing the packaged deck than
re-creating this deck from scratch, so I recommend doing so if you are able to.

## Fields

In order for the code to work, the following named fields must exist in the
deck:

1. Word
2. [Furigana][]
3. Meaning
4. Examples

![Vocabulary Fields][]

All the fields used the default options aside from the following fields:

- Furigana: enabled "Sort by this field in the browser" radio button
- Examples: checked "Remember last input when adding"

## Cards

Each of the files in this directory corresponds to a radio button-ed part of
the Template section of the Card Type for the Anki Deck (which can be accessed
via the `[Cards...]` button in the Fields screenshot above):

- `front-template.html` -> Front Template
- `back-template.html` -> Back Template
- `styling.css` -> Styling

### Front Template

![Vocabulary Front Template][]

### Back Template

![Vocabulary Back Template][]

### Styling

![Vocabulary Styling][]

[Anki]: https://apps.ankiweb.net/
[Anki Packaged Deck]: https://apps.ankiweb.net/docs/manual20.html#exporting-packaged-decks
[CSS]: https://en.wikipedia.org/wiki/CSS
[Furigana]: https://en.wikipedia.org/wiki/Furigana
[HTML]: https://en.wikipedia.org/wiki/HTML
[Japanese Language Proficiency Test]: https://www.jlpt.jp/e/
[Stencil]: https://stencil.fuller.li/en/latest/
[Vocabulary Back Template]: ../../assets/vocabulary-back-template.jpg
[Vocabulary Fields]: ../../assets/vocabulary-fields.jpg
[Vocabulary Front Template]: ../../assets/vocabulary-front-template.jpg
[Vocabulary Styling]: ../../assets/vocabulary-styling.jpg
