# In the Name of — Campaign Wiki

This is the source for the *In the Name of* campaign wiki, a living reference for players to read between sessions and contribute to.

---

## Reading the Wiki

The wiki is hosted at **[inthenameof.dtietze.com](https://inthenameof.dtietze.com/)**.

You can browse it from any browser, on any device. No account or setup required. Pages are linked to each other — clicking a character name, location, or faction will take you to that entry.

---

## Editing the Wiki

Players are welcome to contribute. The wiki is built from a folder of Markdown files that Obsidian reads as a vault. The Obsidian Git plugin handles syncing your changes back to the repository, which automatically deploys to the site.

### What You Need

- [Git](https://git-scm.com/downloads) installed on your machine
- [Obsidian](https://obsidian.md/) (free desktop app)
- The [Obsidian Git plugin](https://publish.obsidian.md/git-doc/Start+here)

### Step 1 — Clone the Repository

Open a terminal and run:

```bash
git clone https://github.com/dtietze/quartz-in-the-name-of.git
```

This downloads the full wiki to your machine.

### Step 2 — Open as an Obsidian Vault

1. Open Obsidian.
2. Click **Open folder as vault**.
3. Navigate to the cloned repository and select the `content` folder inside it.

Obsidian will load all the wiki pages. You can browse, search, and edit them from within the app.

### Step 3 — Install the Obsidian Git Plugin

1. In Obsidian, open **Settings** (gear icon in the bottom left).
2. Go to **Community plugins** and turn off Safe Mode if prompted.
3. Click **Browse**, search for **Obsidian Git**, and install it.
4. Enable the plugin after installation.

The plugin documentation is at [publish.obsidian.md/git-doc](https://publish.obsidian.md/git-doc/Start+here).

### Step 4 — Branch, Edit, and Submit

1. Open the command palette (`Ctrl+P` / `Cmd+P`) and run **Obsidian Git: Create new branch**. Give it a short name (e.g. your name or the page you're editing).
2. Pull the latest changes: run **Obsidian Git: Commit-and-sync** — this also pulls before pushing.
3. Make your edits.
4. When done, open the command palette and run **Obsidian Git: Commit-and-sync** again. This commits your changes, pulls any updates, and pushes your branch to GitHub.
5. Go to the repository on GitHub. You'll see a prompt to open a pull request from your branch — click it and submit.

Changes go live on the site after the pull request is reviewed and merged.

### Tips

- Page titles match file names. To link to another page, type `[[Page Name]]` inside any note.
- If you create a new character, location, ship, or faction, put the file in the corresponding subfolder (`Characters/`, `Locations/`, `Ships/`, `Factions/`).
- Keep entries factual to what has happened in the campaign. DM-only information lives elsewhere.

---

*Built with [Quartz](https://quartz.jzhao.xyz/).*
