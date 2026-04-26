# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repo is

Static GitHub Pages site for the Beachwood Homeowners Association, Inc. (Beachwood subdivision, Wake County, NC), published at `www.beachwoodnc.org`. Content is plain Markdown rendered by GitHub Pages. There is no build step, no framework, and no test suite.

## Content pages

- [index.md](index.md) — homepage: contact info, dues, board members, links to public documents
- [violations.md](violations.md) — violation procedures and fines policy
- [membership_meeting.md](membership_meeting.md) — meeting agenda, budget, proxy voting details

Pages link to each other with relative paths (e.g., `[published procedures](violations)`).

## Utility script

[address to avery.py](address%20to%20avery.py) — generates Avery 5160 mailing-label `.docx` files from `addresses.xlsx`. Run it locally when labels are needed for a mailing. Expects columns: `Display Name`, `Mailing Address`, `City`, `State`, `Zip`.

```bash
pip install pandas python-docx openpyxl
python "address to avery.py"
```

## Governance context

- HOA is a NC not-for-profit corporation governed by Declarations/Covenants and Bylaws (linked from Google Drive in `index.md`).
- The user (Sal LaRocca) is the Treasurer and one of five board members.
- All board seats were last elected November 2025; next election is November 2027.
- Annual dues for 2026: $243.
- Official communication channels are this website, postal mail, and `beachwood.hoa.inc@gmail.com`. No social media.
