# Gustav

> *A named sentient magical codex. Carried by Lyrion Thalor.*
>
> *Gustav is reactive and opinionated; he frequently ruffles his pages and makes disapproving noises as you browse.*

This repository is the shared notebook of the **Crypt Keepers** Dungeons & Dragons campaign — NPCs, locations, items, lore, session recaps, character sheets, party records — collected, organized, and (with great editorial restraint) annotated by the party wizard's codex. The repo is named **Gustav** for that reason: the conceit is that the campaign's accumulated knowledge lives, in-fiction, inside the book. Readers are turning his pages.

The notebook is open to the public. Players, friends, and curious readers welcome. Gustav is, by all accounts, deeply judgmental about who handles him.

> **Spoiler note for players:** the campaign is ongoing. Gustav records everything that has happened so far, including DM canon and in-character secrets. If you are a player and you want to discover things in-fiction, don't read pages your character hasn't reached yet.

## What's in here

| Folder | What it holds |
|---|---|
| `!Meta/` | Campaign-level documents — the [[!Crypt Keepers]] index page, arc summaries (Fish People, Bluefield Burning, Egg Hunt), party height chart, fan-art catalog, meta-joke dossiers |
| `PCs/` | Player character pages — stats, backstory, relationships, per-session log |
| `NPCs/` | Non-player character pages |
| `Cities/` | Major settlements (Fort Elm, Stonewater, Bluefield, Roseview, Zadrid, Autumnbreak) |
| `POIs/` | Points of interest — taverns, shrines, dungeons, ruins, geographic landmarks |
| `Regions/` | Larger geographic units (The Wilds, Iron Peaks, Azadin) |
| `Items/` | Magical items, mundane keepsakes, scrolls, books, vehicles — *including [[Items/Gustav]] himself, who is on the catalog because he insisted* |
| `Lore/` | World-lore concepts (The Weave, Glyph Scar, Loa, Floating Islands) |
| `Recaps/` | Full prose session recaps, numbered campaign-wide |
| `Transcripts/` | WhisperX session-transcript index and excerpts |
| `Attachments/` | Images — character portraits, maps, fan art, reference photos |

The recommended entry point is the index page at `!Meta/!Crypt Keepers.md`. (Gustav prefers if you start there. It's polite.)

## Set up the vault on your computer

For people who have never used Obsidian or Git before. Follow the steps in order.

### 1. Install Obsidian

Obsidian is a free note-taking app that reads markdown files. Download it from **https://obsidian.md** and install it. There are versions for Windows, macOS, and Linux.

### 2. Get a copy of this repository

You have two options. Choose **A** if you just want to read; choose **B** if you want to receive updates automatically as the campaign continues.

#### Option A — Download a one-time copy (simplest)

1. On the GitHub page for this repository, click the green **Code** button near the top right.
2. Choose **Download ZIP**.
3. Save the ZIP somewhere easy to find (e.g. your Documents folder).
4. **Extract the ZIP** (Windows: right-click → Extract All; macOS: double-click). You should end up with a folder called something like `Gustav` or `Gustav-main`.

You can rename that folder to `Gustav` if it isn't already — it doesn't matter to Obsidian, but it preserves the conceit.

To get updates later, repeat the download. You will overwrite your local copy with the newest version.

#### Option B — Clone with GitHub Desktop (easier to keep up to date)

1. Install **GitHub Desktop** from **https://desktop.github.com**.
2. Open GitHub Desktop and sign in with your GitHub account (free).
3. Click **File → Clone repository**, choose this repo from the list (or paste its URL), and pick a folder on your computer to put it in.
4. When the campaign updates and you want the latest version, open GitHub Desktop and click **Fetch origin** → **Pull**. New pages and edits will appear in your local copy automatically.

### 3. Open the folder as an Obsidian vault

1. Open Obsidian.
2. On the welcome screen click **Open folder as vault**.
3. Browse to the `Gustav` folder you downloaded or cloned (the one that contains `README.md` and the `!Meta`, `PCs`, `NPCs`, etc. folders).
4. Click **Open**. Obsidian will index the vault — this takes a few moments the first time you mount it.

The vault is now ready. Open `!Meta/!Crypt Keepers.md` from the file list on the left to get oriented.

### 4. (Recommended) Turn on a couple of useful settings

Inside Obsidian:

- **Settings → Files & Links → New link format**: set to **Shortest path when possible**. This keeps the `[[Wiki Link]]` style consistent with what's already in the vault.
- **Settings → Appearance → Theme**: pick a theme you like. This is per-machine and won't affect anyone else.

## Updating your local copy when new sessions are added

- **If you used Option A (ZIP download):** download the new ZIP, extract it, and replace your old folder. Any per-machine settings you changed in Obsidian are stored locally (in `.obsidian/`, which is *not* tracked by this repo) and will survive the replacement as long as you keep the same folder name in the same location.
- **If you used Option B (GitHub Desktop):** click **Fetch origin** → **Pull** in GitHub Desktop. Obsidian will pick up the new files the next time you open the vault.

## What's *not* in Gustav

A few things are intentionally excluded by `.gitignore`:

- **`.obsidian/`** — your local Obsidian config (open tabs, plugins, themes, hotkeys). Each person's setup is their own; sharing it would overwrite everyone else's preferences every time someone committed.
- **`.trash/`** — Obsidian's local trash folder. If you delete a note locally it goes here; we don't want everyone's deleted-note debris in the shared history. (Gustav approves of the trash bin staying private. Books have *some* dignity.)
- OS junk (`.DS_Store`, `Thumbs.db`, etc.) and editor cruft.

## Conventions

A few patterns the vault uses consistently:

- **`[[Wiki Links]]`** connect pages. `[[Page Name|alias]]` displays "alias" but links to "Page Name".
- **`![[Image.png]]`** embeds an image from `Attachments/`.
- **Session recaps** in `Recaps/` are named `<Title> - Session <N> - <YYYY-MM-DD>.md`. Sessions are numbered **campaign-wide**, not per-arc.
- **Aliases** for misspelled or variant names are recorded at the top of the canonical page (e.g. Baldrin Stoneforge is also recorded as "Baldrun" in some chronicler notes).

## Suggesting fixes or additions

1. **Tell Coldcrow out-of-band** — table chat, Discord, etc. — and the change can be made directly. Issues will be closed. Pull requests will be ignored. This is ultimately a private campaign notebook published in the open; changes are made at the discretion of the author. (Gustav has *opinions* about uninvited editors.)

## License

See [`LICENSE.txt`](LICENSE.txt) for the full text.

## Credits

- **Campaign:** Crypt Keepers
- **DM:** Raiden
- **Players:** Molly, Joey (Coldcrow), Chase (Pursuance), Raine, Jenna, Deadlock (Breadlock), Miranda
- **Librarian / vault maintenance:** Coldcrow (channeling Gustav)
- **The book itself:** [[Items/Gustav]]
