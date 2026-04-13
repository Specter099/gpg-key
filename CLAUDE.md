# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Public GPG key repository for Brian Lauer (key ID `CC8203D9`). Contains the ASCII-armored public key used for verifying signed commits and encrypted communications. No build steps or runtime dependencies.

## Repository Contents

- `Brian Lauer (CC8203D9) – Public.asc` — ASCII-armored GPG public key
- `.github/` — Community health files (issue templates, PR template, Dependabot config)

## Usage

# Import the public key into a local GPG keyring
gpg --import "Brian Lauer (CC8203D9) – Public.asc"

# Verify the key was imported
gpg --list-keys CC8203D9
