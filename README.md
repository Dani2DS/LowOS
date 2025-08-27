# LowOS v0.3.3

**LowOS** is a tiny terminal “OS-like” menu app—just for fun and for learning Python console UX patterns.  
This release cleans up the old 0.3.1TR/0.3.2 builds and packages them for a public GitHub drop.

## Overview
- **Programs:** Calculator (v2.1), Artist (v0.5, no save), Archive (v0.6), Printer (v0.1)
- **Setup:** Password creation + optional tutorial splash (from the 0.3.1TR flavor)
- **Settings:** Change password, guarded crash-test (for dev/testing)

LowOS is self-contained and keeps state only in memory. It does **not** touch the filesystem unless you edit the code to do so.

## What’s new in v0.3.3

- Updated internal year strings (now easy to keep current)
- Adopted the more advanced setup flow from **0.3.1TR**
- Fixed small UX/polish issues (typos, consistent wording)
- Calculator handles division-by-zero gracefully

## Requirements
- **Python 3.9+**
- Optional: `colorama` for colored output (the app still runs without it, just without colors).

Install deps:
```bash
pip install -r requirements.txt
