# homebrew-tap

Homebrew formulae by [@6meowscles](https://github.com/6meowscles).

## Use

    brew tap 6meowscles/tap
    brew install pdfc

## Formulae

- **[pdfc](https://github.com/6meowscles/pdfc)** — a local PDF converter.
  Converts images, text, markdown, HTML and office documents into PDF and
  back out, merges and splits and compresses PDFs, and OCRs scanned ones.
  Everything runs on your machine.

  The install builds PyMuPDF from source, which takes a while. Optional
  tools unlock more conversions and are not installed for you:

      brew install ghostscript tesseract ocrmypdf
      brew install --cask libreoffice

  `pdfc routes` shows which conversions are available and which are blocked.
