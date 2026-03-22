# Promptzy for Mac — Releases

**[Download Promptzy free at promptzy.app](https://promptzy.app)**

---

Promptzy is a native macOS app for managing AI prompts. If you use ChatGPT, Claude, Perplexity, or any other AI tool daily, you've probably retyped the same prompts dozens of times. Promptzy fixes that.

Prompts are stored as plain markdown files on your Mac, so you can reference them from any AI app, link to them directly, and keep everything in one place rather than scattered across browser bookmarks, Notion docs, or your clipboard history.

---

## What this repo is

This is the public release repo for Promptzy. Each tagged release contains:

- Signed `.dmg` installer for macOS
- Auto-update artifacts (used by the in-app updater)
- Release notes

The app itself is closed source. This repo exists so the auto-updater can check for new versions and so users can download specific builds directly.

---

## Why Promptzy

Most AI prompt managers are browser extensions, web apps, or Electron wrappers. Promptzy is a proper native Mac app, built with Tauri, which means it's fast, lightweight, and works the way Mac apps are supposed to work.

A few things that make it different:

**Prompts as markdown files.** Your prompts live on your file system as `.md` files. You own them. You can open them in any editor, back them up however you want, and reference them by file path from any AI tool that supports local file links.

**One place for all your prompts and skills.** Instead of maintaining prompts inside ChatGPT, inside Claude, inside your notes app, you keep one library that any AI app can point to.

**Clipboard wrapping.** Copy something (an email draft, a piece of code, a URL), hit a shortcut, and Promptzy wraps your clipboard content with the prompt you pick and pastes it straight into whichever AI app you're in. No switching windows, no manual copy-paste assembly.

**Dynamic tokens.** Prompts support `{{variable}}` syntax so you can set up templates that prompt you for input before running.

**Hotkey + universal shortcut.** Pull up your prompt library from anywhere on your Mac without switching apps.

**Local and private.** Nothing is sent to a server. iCloud sync is optional if you want your prompts available across devices.

**Free.** No subscription, no paywall.

---

## Download

The latest release is always available at **[promptzy.app](https://promptzy.app)**.

You can also grab a specific version from the [Releases](https://github.com/navbuildz/promptzy-builds/releases) tab above.

**System requirements:** macOS 13 Ventura or later. Apple Silicon and Intel both supported.

---

## Feedback

Found a bug or have a feature request? Open an issue here or reach out via the website. Promptzy is actively developed and early feedback genuinely shapes what gets built next.
