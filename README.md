![Downloads on Zed Extension Store](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fzed-extensions-download-badge.vercel.app%2Fapi%2Fdownloads%3FextensionId%3Dtwig&query=%24.download_count&label=Downloads)

# Twig for Zed

This is a zed extension that enables intellisense and syntax highlighting for the twig templating language.

# Get Emmet to work

Edit your `~/Library/Application\ Support/Zed/extensions/installed/emmet/extension.toml` accordingly:

```toml
[language_servers.emmet-language-server]
language = "HTML"
languages = ["HTML", "PHP", "ERB", "JavaScript", "TSX", "CSS", "Twig"]

[language_servers.emmet-language-server.language_ids]
TSX = "typescriptreact"
HTML = "html"
PHP = "php"
JavaScript = "javascriptreact"
CSS = "css"
ERB = "eruby"
Twig = "twig"
```


## Credits

This extension uses:

- https://github.com/gbprod/tree-sitter-twig for syntax highlighting
- https://github.com/moetelo/twiggy for the language-server

Contributions are welcome!
