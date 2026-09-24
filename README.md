# ErrorControl

VB6 Wise for Windows Installer 4.x error-log interpreter (`ErrorControl.exe`, v2.2) by Dave Robinson (2002). Opens installer error logs with common-dialog / tabbed UI, MSINET, and WebBrowser (`shdocvw`) support for advanced interpretation of Wise MSI error output.

**Source last updated:** 2002-06-01 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `ErrorControl` (`ErrorControl.vbp`) | VB6 | WinForms exe | Wise MSI error log interpreter |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `ErrorControl.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `COMDLG32.OCX`
  - `MSCOMCTL.OCX`
  - `MSINET.OCX`
  - `TABCTL32.OCX`
  - `shdocvw.dll`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/ErrorControl`.
Company names in project files: Dave Robinson. Copyright 2002 Dave Robinson.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
