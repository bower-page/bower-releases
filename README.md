# Bower — downloads

Bower is an AI office suite for macOS and Windows. Documents, spreadsheets,
slides and PDFs, with an assistant that works on the file in front of you.

**[bower.page](https://bower.page)** · **[Download the latest release](https://github.com/bower-page/bower-releases/releases/latest)**

This repository holds the released binaries and nothing else. There is no source
here; it exists so the downloads have a public home.

## Before you install

Neither build is code-signed, so both operating systems will warn you the first
time. `INSTALL.txt` on each release explains what the warning says and what to do
about it — worth reading before you decide the file is broken, because macOS's
wording for this is *"Bower is damaged and can't be opened"* and it isn't.

- **macOS** — Apple Silicon only (M1 or later). There is no Intel build.
- **Windows** — 64-bit Windows 10 or 11.

## The AI needs your own Claude access

Bower's assistant runs on your own Claude subscription through the local `claude`
CLI, or on your own Anthropic API key. The editors work without either; the
assistant doesn't. Your documents are not sent to any server we operate.

What the app does and does not record is written out in full at
**[bower.page/privacy](https://bower.page/privacy)**.
