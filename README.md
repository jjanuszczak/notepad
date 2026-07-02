# Notepad

A browser-hosted Notepad app built with JOG.

This repo contains a small desktop-style text editor that runs fully in the browser. It is intended as a lightweight demo of the **JavaScript Object GUI** ("JOG") runtime and as a usable utility for basic text editing.

## What It Does

- open plain text files from your machine
- edit text in a tabbed workspace
- create multiple documents
- save text back to a file
- show a desktop-style shell with menu, tabs, editor area, and status bar

## Tech Stack

- plain HTML
- plain JavaScript
- `JOG.min.js` runtime
- no backend
- no build step required for basic hosting

## Repo Contents

Typical structure:

```text
/
  index.html
  NotepadApp.js
  JOG.min.js
  README.md