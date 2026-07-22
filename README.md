# AI Image Transparency Tool

A small, browser-based tool for adding a visible AI disclosure badge and transparency metadata to AI-generated images.

The tool runs entirely in the browser. Images are processed locally and are not uploaded to a server.

## Features

* Supports [PNG](https://www.w3.org/TR/png-3/), [JPEG](https://jpeg.org/jpeg/) and [WebP](https://developers.google.com/speed/webp) images
* Adds a configurable AI-generated disclosure badge
* Writes [IPTC Photo Metadata](https://iptc.org/standards/photo-metadata/) and [XMP](https://developer.adobe.com/xmp/docs/) metadata
* Preserves supported existing metadata in update mode
* Supports information about the AI system, prompt, prompt author and credit line
* Records additional processing operations
* Exports the processed image directly in the browser
* Requires no backend or external service

## Live version

The tool is deployed using [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages) and can be used directly in a modern web browser. 

[![Live version](https://img.shields.io/badge/Open%20AI%20Image%20Transparency%20Tool-2563eb?style=for-the-badge)](https://openpotato.github.io/ai-image-transparency-tool/)

## Development

This project — and this README 😊 — was mainly **vibe coded** with the assistance of generative AI. The generated code was subsequently reviewed, tested and manually adjusted.

The tool is intentionally implemented as a single HTML file using plain [HTML](https://html.spec.whatwg.org/), [CSS](https://www.w3.org/Style/CSS/) and [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript).

## Security and provenance

The tool writes unsigned XMP metadata. It does not create a [C2PA](https://c2pa.org/) manifest, digital signature or trusted timestamp.

The metadata therefore provides transparency information, but does not provide cryptographic proof of origin, tamper detection or protection against manipulation.

## Can I help?

Yes, that would be much appreciated. The best way to help is to post a response via the Issue Tracker and/or submit a Pull Request.
