# StruKit for Windows

Portable offline engineering tools and reference libraries for Windows x64.

## Extract and run

Download the Windows ZIP from [Releases](https://github.com/DangerousKitty666/StruKit-Windows/releases). For 0.788 W, use `StruKit-Windows-0.788-x64.zip` and its matching `.sha256` file. Extract the COMPLETE archive into a writable location, then run `StruKit/StruKit.exe`. **No installer or registration is required.** Java and the CAD viewer runtime are included; no development tools are needed.

Keep the `app` and `runtime` folders and `install-manifest.txt` beside the executable. To use another Windows x64 PC, copy the complete StruKit folder or download and extract the ZIP there. Internal Open file works without file associations. See `Read me.txt` for features, recovery and CAD limitations.

## One-time upgrade from 0.786 / 0.787 W

These versions use legacy `7.33.x-PC` tags and cannot discover `v0.788-W`. Manually extract 0.788 and run its executable once. This means extraction, not mandatory installation.

Subsequent updates use **Check for updates > Install update and restart**, replacing managed files in the SAME portable folder the app runs from. No fixed installation path is required. Updates verify the package, stage an independent helper, wait for app exit, back up files and check successful restart, with rollback on failure. User settings are preserved. Keep the portable folder writable.

## Optional Open with registration

On each PC, optionally run `Register file types.cmd` beside the extracted StruKit folder. This registers that copy under Open with and preserves other default apps. If Explorer still opens an old copy, choose **Open with > Choose another app** and select StruKit.exe in your chosen portable folder. Re-register if you later move the folder. Automatic updates keep the same path. Internal Open file never requires registration.

## Separate Windows updates

Starting with 0.788 W, Windows tags use `v<revision>-W` and packages use `StruKit-Windows-<revision>-x64.zip`. The ZIP contains the per-file `install-manifest.txt`; updates also verify GitHub's ZIP digest.

Android remains in [DangerousKitty666/StruKit](https://github.com/DangerousKitty666/StruKit) with an independent release and update feed. Windows releases do not change Android Latest.

## Viewer files

DWG/DXF open in the 2D viewer; STEP/STP/STL/OBJ open in the 3D viewer. Files are processed locally. Displayed geometry and inferred CAD measurements have limitations described in the bundled guide.
