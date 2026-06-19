# Zekke-Maid-Guild-Archive
An archive of documentation for The Guild of Maids in Zekke, a player-driven in-character organization within Project Wayfarer.

## Repository Organization
The root directory should only contain files pertaining to the repo itself and organizational folders.

There are to be four main folders:
* `database` —containing lists, numbers, etc. in machine-parsable formats like `.csv` or `.json`, intended for spreadsheets or other recordkeeping.
* `records` —containing an Obsidian database of github-compatable `.md` files, intended for public viewing.
* `gallery` —containing pictures relevant to the Guild.
* `paperwork` —containing collections of `.txt` files meant to be copy-pasted into SS14 paperwork.

Additionally, the root directory should contain a python script `generate_paperwork.py` that will take key information from `database` and `records` and automatically create/edit files in `paperwork` with proper formatting. (TODO)
