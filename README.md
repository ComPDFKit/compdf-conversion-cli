# compdf-conversion-cli

A Claude Code / Agent Skills-compatible Skill for converting PDF and image files to 10 output formats using the [ComPDFKit Conversion SDK](https://www.compdf.com).

## Features

- **10 Output Formats**: Word, Excel, PPT, HTML, RTF, Image, TXT, JSON, Markdown, CSV
- **PDF & Image Input**: Supports PDF and image files (JPG, JPEG, PNG, BMP, TIFF, TIF, WEBP, JPEG2000)
- **AI Layout Analysis**: Powered by ComPDFKit's document AI model for accurate structure recognition
- **OCR Support**: Automatic OCR for image-based inputs — extracts text from scanned documents and photos
- **Cross-Platform**: Works on Windows and macOS
- **Built-in Trial License**: Includes a trial license (200 conversions) so you can start immediately

## Installation

```bash
npx skills add ComPDFKit/compdf-conversion-cli
```

Or with Claude Code CLI:

```bash
claude mcp add-skill ComPDFKit/compdf-conversion-cli
```

## Prerequisites

- **Python 3.8+**
- **ComPDFKitConversion SDK** — installed automatically via:
  ```bash
  pip install -i https://test.pypi.org/simple/ ComPDFKitConversion
  ```
- **AI Model** (~525MB) — auto-downloaded on first run

## Quick Start

Once installed, the AI agent will automatically use this skill when you ask for document conversion. Example prompts:

- "Convert this PDF to Word"
- "PDF to Excel"
- "Convert image.png to searchable text"
- "Export report.pdf as HTML"
- "Image OCR to text"
- "PDF to PPT"

## Supported Conversions

| Input | Output Formats |
|-------|---------------|
| PDF (.pdf) | Word, Excel, PPT, HTML, RTF, Image, TXT, JSON, Markdown, CSV |
| Images (.jpg/.jpeg/.png/.bmp/.tif/.tiff/.webp/.jp2) | Word, Excel, PPT, HTML, RTF, Image, TXT, JSON, Markdown, CSV |

## License

This skill includes a built-in trial license for evaluation (200 conversions). For production use, purchase a license at [compdf.com/contact-sales](https://www.compdf.com/contact-sales).

The ComPDFKit Conversion SDK is a product of [ComPDF](https://www.compdf.com). See `License.txt` for details.

## Links

- [ComPDFKit](https://www.compdf.com)
- [skills.sh](https://skills.sh)
- [ClawHub listing](https://clawhub.ai/youna12345/compdf-conversion-cli)
