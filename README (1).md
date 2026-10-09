# System Design Primer (Sana Ullah Edition)

A personal study fork of the System Design Primer, maintained as a structured reference for system design interview preparation and software architecture learning.


## Contents

- Core system design concepts (scalability, caching, databases, load balancing, and more)
- Sample system design problems with worked solutions
- Study material available in multiple languages
- A script that compiles the guide into EPUB ebooks

## Prerequisites

- Bash (Linux, macOS, or WSL on Windows)
- [Pandoc](https://pandoc.org/installing.html) version 2.x or later

## Generating the EPUB Files

1. Clone the repository:

```bash
git clone https://github.com/sanaullahcode/system-design-primer.git
cd system-design-primer
```

2. Make the script executable and run it:

```bash
chmod +x generate-epub.sh
./generate-epub.sh
```

The script produces the following files in the project root:

- `README.epub` (English, including solutions)
- `README-ja.epub` (Japanese)
- `README-zh-Hans.epub` (Simplified Chinese)
- `README-zh-TW.epub` (Traditional Chinese)

## Contributing
nder the MIT License. See [LICENSE](LICENSE) for details. 
