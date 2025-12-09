tested on mikrotik v7.20.2

Dynu.com DDNS Updater – API v2  
Tested and working on MikroTik RouterOS v7 (including 7.20.2)

This script updates a single Dynu hostname using the current v2 API.  
It is written in the most compatible way possible so it keeps working even when MikroTik changes the scripting syntax between v7 versions.

Features:
- Safe IP detection (works even if interface has no address)
- Strips the /prefix correctly
- Safe DNS resolve (won’t crash if Internet is down)
- Only updates when the IP actually changed
- No fancy tricks that break in new firmware
- Can be safely pasted line-by-line or all at once

Tested and running without issues on RouterOS 7.20.2 – December 2025
