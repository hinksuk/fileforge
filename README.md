# FileForge

A fast, keyboard-friendly dual-pane file manager for Windows. It looks and behaves like Windows 11 Explorer, with the power tools Explorer leaves out.

## Download

Get the latest version from the **[Releases page](https://github.com/hinksuk/fileforge/releases/latest)**:

| File | What it is |
| --- | --- |
| `FileForge-Setup.exe` | The installer. Recommended for most people. |
| `FileForge-Portable.zip` | The portable version: no installation, and nothing is written to your user profile. |

Requires Windows 10 or 11 (64-bit).

### Installing
Run `FileForge-Setup.exe`. FileForge isn't code-signed yet, so Windows may show **"Windows protected your PC"**. Click **More info → Run anyway**.

### Portable version
Unzip `FileForge-Portable.zip` anywhere, such as a USB stick, and run `FileForge.exe`. Settings, bookmarks and thumbnails are kept in a `FileForge Data` folder next to it. Delete `portable.txt` if you'd rather it used your normal Windows profile.

## Updates
FileForge checks this page for a new release once a day. When one is out, an **Update to x.y.z** button appears in the status bar. Choose **Help → Check for updates** to check straight away.

Every update is signed. FileForge checks each download against a key built into the app and refuses anything that doesn't match. Automatic checking can be turned off in the Updates window.

## Features

**Layout and navigation**
- Two panes side by side or stacked, or a single pane, each with tabs
- Folder tree, bookmark bar with groups, breadcrumbs and a live filter
- Details view, plus icon and thumbnail views in several sizes
- Resizable, reorderable columns: dates created, modified and accessed, attributes, dimensions, date taken, camera, length, artist and album
- Command palette (**Ctrl+Shift+P**): run any command or jump to any folder by typing
- A Windows 11 look with Windows' own icons, or other themes

**Working with files**
- Explorer's own right-click menu and Explorer-style shortcuts
- Find as you type: start typing in any folder to highlight matching names and jump between them
- Drag-to-select, and a selection bar showing count and total size
- A "file already exists" prompt before copying: replace, skip, keep both or rename, one file at a time or for all of them
- Optional copy verification, which reads every copied file back and compares it
- Undo (**Ctrl+Z**) for copy, move, delete and rename
- Browse and restore the Recycle Bin
- Batch rename with stacked rules: insert, remove, numbering, find & replace (including regex), case and extension. Names can come from photo and music details such as date taken, camera, artist and title. Live preview, saved presets and undo.
- A job queue, folder sync and a duplicate finder

**Viewing**
- A preview pane for images, video, audio, PDF, text and code
- Word, Excel, PowerPoint and Outlook files use the same previews as Explorer
- Photo, music and video details

**Archives and networks**
- Open ZIP, 7z, RAR and TAR files like folders. ZIP files can also be edited.
- Network shares (`\\server`), with sign-in when needed
- FTP, FTPS and SFTP, and phones and cameras (MTP)

**Other**
- Optionally start with Windows: open, minimised on the taskbar, or in the tray only
- A transfer window for copies and moves: current-file and total progress, time remaining, a live speed graph, Skip, Pause and Cancel
- Copy progress on the taskbar button, and a pop-out jobs window that can stay on top
- A tray icon: right-click it to jump straight to any of your favourites, and optionally keep FileForge running there when the window is closed
- Can be set as the default file manager, so folders you open elsewhere open in FileForge
- Open PowerShell, Command Prompt or Windows Terminal in the current folder
- A scripting engine and built-in tools: image conversion, checksums and secure delete

## Handy shortcuts

| Keys | Action |
| --- | --- |
| Ctrl+C / Ctrl+X / Ctrl+V | Copy, cut, paste |
| Ctrl+Z | Undo |
| F2 | Rename |
| Delete / Shift+Delete | Recycle / delete permanently |
| Ctrl+Shift+N | New folder |
| Alt+P | Preview pane |
| Ctrl+Shift+P | Command palette |
| Ctrl+Shift+L | Filter the current folder |
| Ctrl+F | Find files |
| Tab | Switch pane |

**Help → Keyboard shortcuts** lists the rest.

## Privacy
FileForge has no accounts, no tracking and no analytics. The only thing it contacts by itself is this GitHub page, once a day, to look for updates, and you can turn that off. Your settings, bookmarks and sign-ins stay on your PC.
