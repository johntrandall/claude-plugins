# johntrandall-plugins

A Claude Code plugin marketplace listing John Randall's public plugins. Each plugin lives in its
own repository, with its own history, issues, licence and releases; this repository only lists
them.

## Add the marketplace

```
/plugin marketplace add johntrandall/claude-plugins
```

Then install a plugin with `/plugin install <name>@johntrandall-plugins`, or browse with `/plugin`.

## Plugins

| Plugin | What it does | Repository |
|---|---|---|
| mermaid | Mermaid syntax reference, SVG/PNG/ASCII rendering, real product icons, and a hook that checks every `.mermaid` write | [claude-plugin-mermaid](https://github.com/johntrandall/claude-plugin-mermaid) |
| mailing-labels | Shipping and return label PDFs onto half-sheet sticker stock, and QR codes or images onto paper (macOS + CUPS) | [claude-plugin-mailing-labels](https://github.com/johntrandall/claude-plugin-mailing-labels) |
| macos-ocr | Text from images and scanned PDFs on macOS: VLM versus OCR engine, Apple Vision helper, embossed cards, safe extraction | [claude-plugin-macos-ocr](https://github.com/johntrandall/claude-plugin-macos-ocr) |
| ptouch-labels | Tape labels on Brother P-touch network printers through the ptouch-label CLI: probing, hi-res, half-cut strips, calibration | [claude-plugin-ptouch-labels](https://github.com/johntrandall/claude-plugin-ptouch-labels) |

Issues about a plugin go to that plugin's repository.

## Licence

This catalog is MIT (see [LICENSE](LICENSE)). Each plugin states its own licence.
