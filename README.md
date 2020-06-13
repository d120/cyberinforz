# Cyber-O-Inforz

Diese Repo enthält die Quelldateien für das Inforz zur Orienttierungsphase als
Webseite. Die Texte sind als Markdown Dateien abgelegt und werden mit [mdBook]
zu einer statische Webseite zusammengebaut.

## Installation

Wenn `cargo` (der Paket-Manager für Rust) installiert ist:

```
cargo install mdbook
```

Ansonsten kann eine Binary auch unter [von GitHub][mdBook/releases]
heruntergeladen werden.

## Testen

Um die Anwendung auf <http://localhost:3000> zu testen:

```
mdbook serve
```

(**Hinweis**: Änderungen an der `inforz.css` Datei werden nicht automatisch neu
geladen)

## Beobachten

Um Änderungen zu beobachten und das Buch neu zu generieren

```
mdbook watch
```

## Bauen

Um das Buch einmalig zu generieren

```
mdbook build
```

[mdBook/releases]: https://github.com/rust-lang/mdBook/releases
[mdBook]: https://rust-lang.github.io/mdBook
