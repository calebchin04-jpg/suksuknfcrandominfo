# Modern Consigliere — Video Production Planning

This repository holds the planning documents for the Modern Consigliere film and website imagery. Everything here is written so you can read it, review it, and make changes to it directly. This page explains how it all works and how to use the tools you have — GitHub, VS Code, and Claude.

---

## What's in here

Everything lives in the **`video production`** folder. Three documents:

| File | What it is |
|------|-----------|
| **`two-worlds-script.md`** | The film script — your voiceover lines, in order, with delivery notes and which "world" (cold/office vs. warm/home) each line plays over. |
| **`two-worlds-recording-guide.md`** | The how-to-film guide — gear, lighting setup, the full shot list, and how to edit the footage together. Written for filming it yourself. |
| **`the-work-image-plan.md`** | The plan for the 12 website images in the "Services" section — what each photo should show and how to shoot them. |

The file extension `.md` just means "Markdown" — a plain text format that displays with nice headings and formatting. You can read and write it like any document.

---

## 🟢 / 🔴 Who films what — the colour code

In **`two-worlds-recording-guide.md`**, every shot in the shot list is tagged with a coloured dot so you know at a glance who records it:

- 🟢 **Green = TIM FILMS.** Any shot **you appear in** — your face, silhouette, or body on camera. You self-record these on the tripod.
- 🔴 **Red = PARTNER FILMS.** Hands, objects, and inserts with **no one identifiable on camera.** Your camera partner records these.

**Why dots and not coloured text?** GitHub and phone screens don't display custom font colours in these documents — if the text were literally coloured green or red, it would just show up black when you review it. The 🟢 and 🔴 dots read as colour everywhere, so the signal never gets lost.

If you'd rather split the shots differently — say, you want to record some of the hands shots yourself too — just tell Claude and it will re-tag them.

---

## Reading the documents (the fast way)

You're already in the right place. To read anything:

1. Click the **`video production`** folder above.
2. Click any file. GitHub displays it fully formatted — no downloads, no tools needed.

That's all you need to review everything. The rest of this guide is for when you want to **change** something.

---

## Making changes — three ways, easiest first

### Option 1 — Ask Claude to do it *(recommended)*

You have Claude as an assistant, and it can handle all of this for you. You don't need to learn any commands. Just tell it plainly what you want, for example:

> "Open the film script and change the line 'let's work' to 'let's begin.'"

> "In the recording guide, add a note that I'm shooting on an iPhone."

> "In the image plan, swap the compass idea in Panel 4 for a wristwatch."

Claude will make the edit and save it so it shows up here on GitHub for everyone. When you want your changes to appear on this page, just say **"save and push my changes"** and it will take care of it.

### Option 2 — Edit directly here on GitHub

Good for quick text tweaks, no software needed:

1. Open the file you want to change.
2. Click the **pencil icon** (top-right of the file).
3. Edit the text.
4. Click the green **"Commit changes"** button. ("Commit" just means "save.") Your change is now live.

### Option 3 — Edit in VS Code

Best when you want to work on several files at once, on your own computer.

**First time — getting the files onto your computer:**
1. At the top of this repository, click the green **`< > Code`** button, then **"Open with GitHub Desktop"** or copy the web address shown.
2. In VS Code, open the Command Palette (press `Cmd` + `Shift` + `P` on Mac), type **"Git: Clone,"** paste the address, and choose a folder. This downloads a copy — called *cloning*.
3. VS Code will offer to open the folder. Say yes.

**Editing:**
- Click any file in the left sidebar, edit it, and save (`Cmd` + `S`).

**Sending your changes back so they appear here:**
- Click the **Source Control** icon on the left (it looks like a branching line).
- Type a short note describing what you changed, click **"Commit,"** then **"Sync"** (or "Push").
- Or — simplest — just ask Claude: **"save and push my changes."**

---

## A few words you'll see, in plain terms

- **Repository (or "repo")** — this whole project folder, stored online.
- **Clone** — download a copy to your computer.
- **Commit** — save a change, with a short note about what it was.
- **Push / Sync** — send your saved changes back here so others see them.
- **Markdown / `.md`** — the plain-text document format these files use.

You don't need to memorize any of this. If you ever get stuck or unsure, ask Claude — describe what you're trying to do in normal words, and it will walk you through it or just do it for you.

---

## The short version

1. **Read** anything by clicking into the `video production` folder.
2. **Change** anything by telling Claude what you want, or using the pencil icon on GitHub.
3. **Ask Claude** whenever you're unsure — that's what it's there for.
