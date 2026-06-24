# NealNote Studio

NealNote Studio is a local-first desktop app that turns YouTube video URLs into
clean transcript files and professional Word document briefs.

This public repository is only for beta downloads and product information. The
source code repository remains private during the beta period.

## Latest Beta

Version: `v1.3.1`

Download for Windows:

- [NealNote-Studio-1.3.1-x64.exe](https://github.com/irkneal/nealnote-downloads/releases/download/v1.3.1/NealNote-Studio-1.3.1-x64.exe)

SHA-256:

```text
55505a0df24d74c547f41ea44945afb6c32b3a0c02a8c90b9c937697439ad89e
```

## What It Does

- Accepts a YouTube video URL.
- Generates a cleaned transcript file.
- Generates a professional Word document brief.
- Saves output files locally on the user's machine.
- Runs through a simple desktop UI.

## Beta Notes

- Windows desktop beta only.
- The app is unsigned in this beta release, so Windows may show a security
  prompt before first launch.
- Generated documents stay local.
- No source code is published in this repository.

## Verify The Download

PowerShell:

```powershell
Get-FileHash .\NealNote-Studio-1.3.1-x64.exe -Algorithm SHA256
```

The hash should match:

```text
55505a0df24d74c547f41ea44945afb6c32b3a0c02a8c90b9c937697439ad89e
```

## Project Status

`v1.3.x` is the UI beta line for NealNote Studio. It verifies the browser Studio
and Windows desktop app flow before broader public distribution.
