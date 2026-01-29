# IPTV Test Channel List

This repository contains a simple list of TV channels used for testing an IPTV application. The main goal is to have a lightweight, versioned source of channel data that can be consumed by different IPTV clients during development.

## Purpose

- Test and debug IPTV player features (EPG, zapping, buffering, error handling, etc.).
- Experiment with different UI layouts and metadata handling.
- Keep channel data in one central place that can be updated independently of the app code.

## Data format

The channels are stored in a machine-readable format (for example JSON, M3U, or similar), so they can be easily parsed by the app. Each entry typically includes:

- Channel name  
- Stream URL  
- Optional logo/icon URL  
- Optional category or group  

Check the channel list file in this repository for the exact structure.

## Usage

You can use this repository in your IPTV app or tools by:

1. Cloning the repository or adding it as a submodule.
2. Pointing your app’s configuration to the channel list file.
3. Reloading or rebuilding your app to pick up the changes.

This repository is intended for **testing and development purposes only**, not for production IPTV services.

# IPTV Test Channel List

## 🎥 Main Playlist 
[![Playlist](https://img.shields.io/badge/Live-Playlist-blue?style=flat&logo=play-circle)](https://raw.githubusercontent.com/liviurhos/tv-channel-playlist/main/tvChannels1playlist.m3u)

**[tvChannels1playlist.m3u](https://raw.githubusercontent.com/liviurhos/tv-channel-playlist/main/tvChannels1playlist.m3u)**

Copy-paste the link above directly into any IPTV player (VLC, Kodi, GSE Smart IPTV, TiviMate, etc.).

## Usage Examples

**Direct link for apps:**
https://raw.githubusercontent.com/liviurhos/tv-channel-playlist/main/tvChannels1playlist.m3u

**In Kodi/TiviMate/VLC:**
1. Open your IPTV app
2. Add M3U Playlist → paste the RAW link
3. Load & Play

## Updates

The channel list may be updated from time to time (new channels added, broken links removed, metadata adjusted). There is no fixed update schedule, so treat this as a best-effort test source rather than a guaranteed stable feed.

## Disclaimer

All streams and channel entries included here are provided strictly for development and testing.  
If you use or redistribute this list, you are responsible for ensuring you comply with all applicable laws, terms of service, and content rights.
