DYLAN VGC Roller — Supabase + linked wheel data

The page automatically loads "adjusted prob.wheel" from the same folder when it opens.
That file supplies the wheel option names, embedded images, and probability weights.

IMPORTANT:
- Keep index.html and adjusted prob.wheel in the same folder.
- On GitHub Pages, upload both files to the same repository/folder.
- The browser will fetch adjusted prob.wheel automatically; no manual Load Wheel step is needed.
- If you edit the .wheel file and reload the page, the updated data will be used.
- Both players should use the same adjusted prob.wheel file for shared sessions.

Supabase:
- Realtime Broadcast is already configured in index.html.
- No database table is required for the shared spin feature.
- The browser uses the Supabase publishable key, not a secret/service-role key.
