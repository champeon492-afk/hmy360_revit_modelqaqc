# Hemy 360 Model QA/QC for Revit 2027

This repository preserves the Hemy 360 Model QA/QC Revit add-in package supplied in `Hemy360ModelQAQCRevit2027.zip`.

## Package contents

- `Hemy360.Qaqc.addin` — Revit add-in manifest
- `Hemy360.Qaqc/Hemy360.Qaqc.dll` — compiled plugin
- `Hemy360.Qaqc/Hemy360.Qaqc.pdb` — debug symbols
- `Hemy360.Qaqc/README.md` — original project documentation

## Install

Extract the ZIP into `%APPDATA%\Autodesk\Revit\Addins\2027\` so that `Hemy360.Qaqc.addin` sits directly in that folder and the DLL is in its `Hemy360.Qaqc` subfolder. Restart Revit 2027, then open **Hemy 360 → Model QA/QC**.

## Source availability

The supplied ZIP does **not** contain the C# source files, project file, tests, or installer scripts mentioned in its internal README. This repository currently stores the compiled package only. To publish editable source, the original `src/Hemy360.Qaqc`, `tests/Hemy360.Qaqc.Verify`, and `installer` folders must be recovered from the development project.
