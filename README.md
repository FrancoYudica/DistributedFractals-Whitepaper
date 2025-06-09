# DistributedFractals-Whitepaper

This repository contains the whitepaper for the [DistributedFractals](https://github.com/FrancoYudica/DistributedFractals) project, a distributed computing system designed to render fractals efficiently across multiple nodes.

The whitepaper outlines the architecture, implementation details, and performance considerations of the DistributedFractals system. It also discusses the problem space, motivation, and future work for the project.

## 📄 About the Whitepaper

The whitepaper is written in Spanish (`whitepaper_esp.md`) and aims to provide a comprehensive explanation of the system's goals, design decisions, and technical challenges. It serves both as documentation for developers and as a theoretical foundation for the project.

## 🔗 Source Code

You can find the full source code of the project here:
👉 [DistributedFractals GitHub Repository](https://github.com/FrancoYudica/DistributedFractals)

## 🛠️ Building the Whitepaper

Although the whitepaper is written in Markdown, it requires [Pandoc](https://github.com/jgm/pandoc) for proper rendering into PDF format due to its use of advanced LaTeX features.

To build the whitepaper:

```bash
pandoc whitepaper_esp.md -o whitepaper.pdf --pdf-engine=xelatex --include-in-header=header.tex --number-sections
```

Make sure you have pandoc and xelatex installed on your system.
