# Torrent Studio — Seedr Account Onboarding

This repository is the onboarding-preview branch for Torrent Studio. It is intentionally configured to require each user to use their own Seedr account and does not contain developer Seedr credentials.

## Current preview
- Welcome screen explains that a personal Seedr account is required.
- `Create Seedr Account` opens Seedr.
- `I already have an account` moves to a clear connection-preview screen.
- The preview never asks for a Seedr password or API token.
- The preview does not use another user's Seedr storage.

The actual per-user Seedr OAuth/API authorization flow is a separate implementation step.
