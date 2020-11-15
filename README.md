# JLPT Anki Deck Templates

This repository contains sample templates and code for [Anki][] flash card decks
that I used to study for [level N1][JLPT level list] of the [Japanese Language
Proficiency Test][] (JLPT).

![Kanji Back Template][]

I used the [新完全マスター][] (_Shin Kanzen Master_) series of books as a basis
to create my flash card decks; meaning that I straight-up adapted all content
from all the books into flash card decks.

Therefore, regardless of my desire to want to share the entire content of the
decks online, it would not be fair to the book authors, and I'm sure the book
publishers would not be so happy with me if I did.

So, instead, if you are studying for JLPT Level N1, I would strongly encourage
you to purchase the books (or any others that may suit you better) and then make
your own Anki decks out of them, using or adapting the templates in this
repository, or making your own.

This has the great benefits of:

- making the content more portable: you are not limited by the form-factor or
  non-search-ability of the books (if you are on iOS, you may think that
  [AnkiMobile][] is pricey for "just an app", but it is worth it for the
  objective you are trying to achieve)
- enabling Anki to work its spaced-revision-ing algorithms over the content,
  surfacing your weaknesses and making sure they improve
- adapting the book content to flash cards **_is a form of study_**, and will
  assist greatly in your learning/revision of the content

## How to use the templates

Right click on any of the `.apkg` files in this repository, and save the file to
your computer.

Double-click on the file and it should open up the deck in Anki, where you can
then add individual cards as you please.

## How to use the templates (advanced/technical)

If you want to delve a bit deeper into the code in each deck and are familiar
with your computer's [command line interface][] (eg Terminal/Command Prompt),
then:

```sh
git clone git@github.com:paulfioravanti/jlpt.git
cd jlpt
```

Open the directory with your favourite text editor, and see the `src/` directory
for the sets of files related to each Anki deck.

There is a `README.md` file in each directory that should be able to help you if
you wanted to re-create the decks from scratch.

Good luck with your exam preparations! 頑張れ〜！🎌

[Anki]: https://apps.ankiweb.net/
[AnkiMobile]: https://apps.apple.com/au/app/ankimobile-flashcards/id373493387
[command line interface]: https://en.wikipedia.org/wiki/Command-line_interface
[Japanese Language Proficiency Test]: https://www.jlpt.jp/e/
[JLPT level list]: https://www.jlpt.jp/e/about/levelsummary.html
[Kanji Back Template]: ./assets/kanji-back-template.jpg
[新完全マスター]: https://www.3anet.co.jp/np/list.html?series_id=4&af=1&g=5&s=4
