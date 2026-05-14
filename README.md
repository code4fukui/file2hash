# file2hash

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple, client-side web application for calculating file hashes. Drag and drop a file to instantly generate SHA-512, SHA-256, SHAKE-128, and MD5 hashes. All processing is done locally in your browser; your files are never uploaded.

## Demo

**[Live Demo](https://code4fukui.github.io/file2hash/)**

## Features

-   **Multiple Algorithms:** Calculates SHA-512, SHA-256, SHAKE-128 (128-bit), and MD5 hashes.
-   **Multiple Formats:** Displays each hash in both Base32 and Base16 (hexadecimal) formats.
-   **File Info:** Shows the input file size in bytes.
-   **Easy to Use:** Simple drag-and-drop interface.
-   **Secure & Private:** All calculations are performed client-side. Files are not uploaded to any server.

## Usage

1.  Visit the [demo site](https://code4fukui.github.io/file2hash/).
2.  Drag and drop a single file anywhere onto the page.
3.  The file size and calculated hashes will instantly appear in the corresponding text fields.

## Dependencies

This tool is built with several open-source libraries:

-   [SHA512](https://github.com/code4fukui/SHA512)
-   [SHA256](https://github.com/code4fukui/SHA256)
-   [SHAKE128(SHA3)](https://github.com/code4fukui/SHA3)
-   [MD5](https://github.com/code4fukui/MD5)
-   [Base32](https://github.com/code4fukui/Base32)
-   [Base16](https://github.com/code4fukui/Base16)

## License

MIT License — see [LICENSE](LICENSE).