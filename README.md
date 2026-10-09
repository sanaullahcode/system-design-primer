# System Design Primer: Sana Ullah 

> Understanding large systems by breaking them into smaller parts. This repository is a personal study guide for learning system design step by step.

This fork is based on [System Design Primer](https://github.com/sanaullahcode/system-design-primer). It adds an EPUB build pipeline on top of the original content, so the full guide can be read offline as an ebook.

---

## Purpose of This Guide

The goal is not only interview preparation. The goal is to understand how large platforms such as Google, Netflix, and others are designed and operated. Each concept is broken into small, clear sections.

## What Is Included

- **Fundamentals:** scalability, latency vs. throughput, availability vs. consistency, CAP theorem
- **Building blocks:** caching, load balancers, databases (SQL and NoSQL), message queues, CDNs, reverse proxies
- **Case studies:** worked solutions for a range of system designs
- **Trade-offs:** the benefits and drawbacks behind each design choice
- **Translations:** Japanese, Simplified Chinese, and Traditional Chinese

## Suggested Learning Path

If you are new to this guide, follow this order:

1. Scalability and core performance concepts
2. Storage and database fundamentals
3. Caching and load balancing
4. Asynchronous processing and message queues
5. Smaller case studies (URL shortener, chat system, news feed)
6. Larger case studies and trade-off analysis

## Generating the EPUB Ebook

### Requirements

- Bash (Linux, macOS, or WSL on Windows)
- [Pandoc](https://pandoc.org/installing.html) version 2.x or newer

### Steps

```bash
git clone https://github.com/sanaullahcode/system-design-primer.git
cd system-design-primer
chmod +x generate-epub.sh
./generate-epub.sh
```

The script produces the following files:

| File | Language |
|---|---|
| `README.epub` | English (including solutions) |
| `README-ja.epub` | Japanese |
| `README-zh-Hans.epub` | Simplified Chinese |
| `README-zh-TW.epub` | Traditional Chinese |

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request. Small fixes such as typo corrections and clearer explanations are just as valuable as larger changes, so bug reports and documentation fixes are also welcome.

For translations, see [TRANSLATIONS.md](TRANSLATIONS.md).

## Acknowledgements

- Sana Ullah creator and maintainer of the original project
- All translation maintainers and contributors who have improved this project

## License

The code in this fork is licensed under the [MIT License](LICENSE). The original content is subject to the license set by its upstream author. Please review the upstream repository's `LICENSE` file before redistributing the content.
