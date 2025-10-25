---
title: "Installation Guide"
layout: default
---

# Installation Guide

## System Requirements

- **Architecture:** x86_64 (64-bit)
- **CPU:** 2 GHz dual-core processor or better
- **RAM:** 2 GB minimum (4 GB recommended)
- **Storage:** 20 GB available space
- **Display:** 1024x768 resolution or higher

## Quick Installation

1. **Download** the Apliko Linux ISO
2. **Create bootable USB** using:
   ```bash
   # Using dd on Linux
   sudo dd if=apliko-linux-1.0.0.iso of=/dev/sdX status=progress
   
   # Using Rufus on Windows
   # Select the ISO and write to USB
