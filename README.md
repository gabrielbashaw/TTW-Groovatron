# Groovatron TTW Compatibility Patch

Compatibility patch for **The Groovatron** enabling proper functionality with **Tale of Two Wastelands (TTW)**.

This patch resolves initialization issues that prevented Groovatron items and systems from being correctly distributed when starting a TTW playthrough from the Fallout 3 side.

> This is an ESP-only patch. Original Groovatron assets are still required.

---

# Nexus Mods Release

Download the released version here:

[Groovatron TTW Compatibility Patch on Nexus Mods](https://www.nexusmods.com/newvegas/mods/78084?)

---

# Overview

The original Groovatron setup relied on New Vegas initialization behavior that does not execute correctly within TTW until the player transitions into the Mojave.

As a result:
- required Groovatron items were not added correctly
- core functionality remained inaccessible
- users had to enter New Vegas before the mod initialized properly

This patch modifies plugin behavior to ensure Groovatron initializes correctly during TTW startup progression, including Fallout 3 starts.

---

# Technical Details

## Problems Addressed
- TTW initialization timing conflicts
- Cross-game plugin compatibility issues
- Runtime item distribution failures
- Dependency/load-order interactions

## Compatibility Tested With
- Tale of Two Wastelands (TTW)
- NVSE
- The Groovatron Fallout 3
- The Groovatron Fallout New Vegas

The patch preserves original Groovatron functionality while improving compatibility with TTW environments.

---

# Features

The Groovatron allows players to:
- Trigger animation poses on player or NPCs
- Assign hotkeys to animations
- Move and manipulate NPC behavior
- Temporarily neutralize hostile NPCs
- Access NPC inventories
- Clone or freeze NPCs
- Use integrated MP3 playback
- Access a portable companion-friendly player home

This patch focuses specifically on ensuring those systems initialize correctly under TTW.

---

# Requirements

## Required
- The Groovatron Fallout 3
- The Groovatron Fallout New Vegas
- NVSE

## Optional (Recommended)
- F3 Umpa Animation 0.7a by umpa
- LostRider For a Few Poses More NV
- LostRider Slave In Pose NV
- Poses By Sari-December

---

# Installation

## 1. Install Required Mods

Install:
- The Groovatron Fallout 3
- The Groovatron Fallout New Vegas

Optional:
- LostRider For a Few Poses More NV
- LostRider Slave In Pose NV
- Poses By Sari-December

---

## 2. Overwrite Files

Allow:
- The Groovatron NV

to overwrite:
- The Groovatron Fallout 3

---

## 3. Disable Existing ESPs

Disable or remove:
- TheGroovatron.esp
- TheGroovatronNV.esp

If installed, also disable:
- F3umpaAnimation.esp
- FewPosesMore NVedition.esp
- Slave In Pose NV Edition.esp
- SariDposesNV.esp

---

## 4. Install Patch

Replace:
- TheGroovatronNV.esp

with the patched version from this repository.

---

## 5. Launch Game

After receiving the Pip-Boy on a new TTW save, wait approximately 15 seconds for initialization scripts to complete and required items to be added.

---

# Community Impact

- 1.2k+ unique downloads
- Publicly released compatibility patch
- Supports TTW modded playthroughs
- Maintained for community use

---

# Credits

Original Groovatron created by Drayk_Cannon.  
Fallout New Vegas port by Koupoable.

This repository only contains compatibility modifications required for TTW integration.

Original assets are not redistributed.

---

# License / Distribution

Please support and endorse the original mod authors if you enjoy their work.

This patch is intended solely for compatibility purposes and requires the original Groovatron releases.
