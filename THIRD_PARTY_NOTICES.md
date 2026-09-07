# Third-Party Notices

NoveMD uses and can optionally install open-source components. Their licences apply to those components only and do not change the licence of NoveMD itself.

This file highlights the principal components whose use or distribution needs additional explanation. The distributed application also includes per-package licence and notice materials for its runtime dependencies, together with the Electron and Chromium licence notices. Those component-specific terms remain authoritative for the corresponding third-party code.

## ColaMD

- Project and source: https://github.com/marswaveai/ColaMD
- Licence: MIT License
- Copyright (c) 2026 marswave.ai

ColaMD provided early inspiration for NoveMD. NoveMD is independently branded and developed. The original copyright and permission notice is retained below as required by the MIT License.

## Pandoc (optional component)

- Project: https://pandoc.org/
- Source and releases: https://github.com/jgm/pandoc
- Licence: GNU General Public License, version 2 or later
- Managed version currently offered by NoveMD: 3.10.1

Pandoc is not included in the default NoveMD installer. If the user chooses “Install optional Pandoc”, NoveMD downloads the unmodified official Windows archive from the Pandoc GitHub release, verifies its SHA-256 digest, and installs it under the current user’s application-data directory. The downloaded distribution contains Pandoc’s licence and copyright materials.

Users may instead select an existing Pandoc installation. Removing NoveMD does not necessarily remove an optional Pandoc component stored in application data.

## MathJax

- Project and source: https://github.com/mathjax/MathJax-src
- Licence: Apache License 2.0

NoveMD uses MathJax locally to render mathematical notation. Formula rendering does not require an online service.

## Mermaid

- Project and source: https://github.com/mermaid-js/mermaid
- Licence: MIT License

NoveMD uses Mermaid locally to render supported diagrams.

## Anydoc

- Project and source: https://github.com/firecrawl/anydoc
- Licence: MIT License
- Copyright (c) 2026 Sideguide Technologies Inc.

NoveMD uses Anydoc locally to read supported office, OpenDocument, RTF, EPUB and spreadsheet files. NoveMD's Markdown serializer contains adapted logic from Anydoc's MIT-licensed renderer.

## PDF Inspector

- Project and source: https://github.com/firecrawl/pdf-inspector
- Licence: MIT License
- Copyright (c) 2026 Firecrawl

NoveMD uses PDF Inspector locally to classify and extract text from text-based PDF files. Scanned or image-only PDF files are not silently sent to an online OCR service.

## PDF.js

- Project and source: https://github.com/mozilla/pdf.js
- Licence: Apache License 2.0
- Copyright: Mozilla Foundation and PDF.js contributors

NoveMD uses PDF.js locally to identify and render PDF pages whose images,
diagrams or scanned content cannot be represented by editable text alone.
Documents are not uploaded to a rendering service.

## @napi-rs/canvas

- Project and source: https://github.com/Brooooooklyn/canvas
- Licence: MIT License
- Copyright: @napi-rs/canvas contributors

NoveMD uses @napi-rs/canvas locally as the raster surface for retained PDF
page visuals.

## Kordoc

- Project and source: https://github.com/chrisryugj/kordoc
- Licence: MIT License
- Copyright (c) 2026 chrisryugj

NoveMD uses the non-OCR document parsing portion of Kordoc for supported Hangul document imports. Kordoc includes or derives portions from additional open-source projects; its distributed `NOTICE` and third-party licence materials apply to those portions.

## MIT licence text for ColaMD, Anydoc, PDF Inspector, @napi-rs/canvas and Kordoc

Permission is hereby granted, free of charge, to any person obtaining a copy of these software components and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The applicable copyright notice above and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
