# bit.tmLanguage

TextMate grammar for the [Bit programming language](https://bitlang.org).

- Grammar: `syntaxes/bit.tmLanguage.json`
- Scope name: `source.bit`
- File extension: `.bit`

This is the single source of the grammar. The
[Bit VS Code extension](https://github.com/byteink/bit/tree/main/editors/vscode)
and [github-linguist](https://github.com/github-linguist/linguist) both consume
this repository, so edit the grammar here and sync it outward — never the other
way round.

## Use it

Point any TextMate-compatible editor at `syntaxes/bit.tmLanguage.json`.
`language-configuration.json` carries the bracket, comment and auto-closing
rules for editors that read VS Code's format.

## Licence

MIT — see [LICENSE](LICENSE).
