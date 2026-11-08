# StruKit for Windows

Offline engineering tools and reference libraries for Windows x64.

## Download and run

Download the Windows ZIP from [Releases](https://github.com/DangerousKitty666/StruKit-Windows/releases), extract the entire archive, then run `StruKit/StruKit.exe`. Java and the CAD viewer runtime are included.

Revision 0.786 W includes the non-viewer Android 0.785 tools and reference assets, adapted for desktop use. See the release notes and bundled `Read me.txt` for details, validation and CAD limitations.

## Separate Windows updates

This repository hosts Windows releases. The Windows app checks this repository for updates. Android remains in [DangerousKitty666/StruKit](https://github.com/DangerousKitty666/StruKit) with an independent release feed.

Windows release tags use `v<internal-version>-PC`; packages use `StruKit-Windows-<internal-version>-x64.zip`. Visible revision 0.786 W uses internal updater version 7.33.2.

## File associations

Optional: run `Register file types.cmd` beside the extracted StruKit folder to add Open with entries for DWG, DXF, STEP, STP, STL and OBJ. Existing defaults are preserved.
