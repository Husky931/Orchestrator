# TOOLS.md - Local Notes

Skills define _how_ tools work. This file is for _your_ specifics — the stuff that's unique to your setup.

### SSH

- home-server → 192.168.1.100, user: admin

## Transcription

- **whisper.cpp** (medium model) — local, free voice-to-text
  - Binary: `/usr/local/opt/whisper-cpp/bin/whisper-cli`
  - Model: `/usr/local/bin/whisper-models/ggml-medium.bin`
  - Used for: WhatsApp voice message transcription

## Agent Commands

- **Banker agent**: `openclaw agent --agent banker --message "..."`
  - Use this to forward expense messages to The Banker
  - Example: `openclaw agent --agent banker --message "35.7 RMB for cocoa milk shake"`

Add whatever helps you do your job. This is your cheat sheet.
