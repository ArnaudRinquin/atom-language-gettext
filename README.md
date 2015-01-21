# Gettext files support in Atom

Adds syntax highlighting to `msgid`, `msgstr`, etc in Atom.

Adds a few snippets:

* `id` -> `msgid "$1"`
* `str` -> `msgstr "$1"`
* `ctx` -> `msgctxt "$1"`
* `msg` -> `msgid + msgstr`
* `msgc` -> `msgctxt + msgid + msgstr`

The last `tab` navigation position is conveniently placed on a new line so you can chain quickly.

Originally [converted](http://atom.io/docs/latest/converting-a-text-mate-bundle)
from the [Gettext TextMate bundle](https://github.com/textmate/gettext.tmbundle).

Contributions are greatly appreciated. Please fork this repository and open a
pull request to add snippets, make grammar tweaks, etc.
