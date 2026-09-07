# RabbitSVN Releases

Compiled macOS builds of **RabbitSVN** — a native SwiftUI Subversion (SVN) client for macOS, inspired by TortoiseSVN and SmartSVN.

This repository hosts only the compiled release binaries. It does not contain source code.

## Download

Grab the latest `.zip` from the [Releases](../../releases) page, unzip it, and move `RabbitSVN.app` to `/Applications`.

## First launch (Gatekeeper)

RabbitSVN.app is not code-signed or notarized. macOS Gatekeeper will block the first launch with "cannot verify developer". To open it:

- Right-click `RabbitSVN.app` → **Open** → confirm in the dialog, or
- Run in Terminal:
  ```bash
  xattr -cr /Applications/RabbitSVN.app
  ```

## Requirements

- macOS 13 or later
- The `svn` command-line tool (RabbitSVN can install it automatically on first launch if missing)

## Updates

RabbitSVN checks this repository's [Releases](../../releases) page for new versions.

## About

Developed by [Kaito Vu](https://github.com/Kaito-Vu).
