# Millennium — install on a Mac

1. Pick the right file:
   - **Apple Silicon (M1/M2/M3/M4):** `Millennium-mac-arm64.zip`
   - **Older Intel Mac:** `Millennium-mac-x64.zip`
   (Apple menu → About This Mac → "Chip" or "Processor".)
2. Double-click the zip. Drag **Millennium.app** into **Applications**.
3. The app is not signed by Apple, so the first time: **right-click (or Control-click) Millennium → Open → Open**.
4. If macOS says the app "is damaged" or still blocks it, open **Terminal** and run:
   ```
   xattr -cr /Applications/Millennium.app
   ```
   Then open it normally.

## First sign-in
- Staff **Yonas Tesfay (Admin)**, PIN **1234**. You will be asked to choose a new PIN.
- The app opens with demo data. To start fresh: Settings → Demo data → Clear demo data.

## Your data
- Everything is stored on this Mac, fully offline:
  `~/Library/Application Support/Millennium/`
- A backup is made on start, every 2 hours, and on quit (newest 10 kept).
- Settings → Backup & restore → "Save a copy to a file / USB" for an extra copy.

Made by 9 Multimedia and IT solutions (SHAMM TESFALEM) · TEL. 07162947
