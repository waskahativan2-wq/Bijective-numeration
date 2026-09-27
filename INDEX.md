# Bijective Numeration

> A clear reference index for the Bijective-numeration project.

## Overview

Bijective numeration is a positional number system with no zero digit. This project focuses on the relationship between ordinary base-26 values using digits 0–25 and bijective base-26 values using symbols A–Z, where A = 1 and Z = 26.

The notation is commonly used for spreadsheet columns and other human-readable numbering systems.

## Current Repository

The repository is currently in an early documentation stage. The files listed below under Planned Structure are proposed additions and should be linked here after they are created.

## Quick Reference

| Bijective value | Decimal value | Example |
|---:|---:|---|
| A | 1 | First symbol |
| B | 2 | Second symbol |
| Z | 26 | Last single-letter symbol |
| AA | 27 | First two-letter value |
| AB | 28 | Next value |
| AZ | 52 | Two-letter value |
| BA | 53 | Following value |

## Planned Structure

```text
Bijective-numeration/
├── README.md                  Project overview
├── INDEX.md                   Repository index
├── docs/
│   ├── CONCEPTS.md            Mathematical concepts
│   ├── CONVERSION_GUIDE.md    Conversion instructions
│   └── EXAMPLES.md            Worked examples and use cases
├── src/
│   ├── bijective.py           Python implementation
│   └── bijective.js           JavaScript implementation
├── tests/
│   ├── test_bijective.py      Python tests
│   └── test_bijective.js      JavaScript tests
└── FILEMANIFEST.md            Detailed file descriptions
```

## File Manifest

| File or directory | Status | Purpose |
|---|---|---|
| [`README.md`](README.md) | Present | Project overview |
| [`INDEX.md`](INDEX.md) | Present | Navigation and reference index |
| `docs/` | Planned | Concepts, guides, and examples |
| `src/` | Planned | Conversion implementations |
| `tests/` | Planned | Automated tests |
| `FILEMANIFEST.md` | Planned | Detailed file inventory |

## Navigation

- [Project README](README.md)
- [Concepts and theory](docs/CONCEPTS.md)
- [Conversion guide](docs/CONVERSION_GUIDE.md)
- [Examples](docs/EXAMPLES.md)
- [Python implementation](src/bijective.py)
- [JavaScript implementation](src/bijective.js)
- [Tests](tests/)

> Links to planned files will become active when those files are added to the repository.

## Project Goals

1. Define bijective base-26 notation clearly.
2. Document conversion between decimal and alphabetic representations.
3. Provide small, readable implementations.
4. Include examples that are easy to verify by hand.
5. Add tests for edge cases such as Z → AA and AZ → BA.

## Roadmap

- [ ] Document the mathematical model
- [ ] Add decimal-to-bijective conversion
- [ ] Add bijective-to-decimal conversion
- [ ] Add input validation
- [ ] Add Python and JavaScript tests
- [ ] Expand examples and usage documentation
- [ ] Add a license and contribution guidelines

## Display Notes

This file uses standard GitHub-flavored Markdown, so it is designed to remain readable on both desktop and mobile screens:

- Tables are kept compact for narrow screens.
- Code blocks preserve alignment across devices.
- Links use relative paths so they work from the repository.
- Sections are short and easy to scan.

---

**Last updated:** September 27, 2026
