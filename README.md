# schedule

Eduardo A. Morcillo (Edanmo) VB6 Task Scheduler Class v1.01 (`Schedule.dll` / `TaskScheduler` ActiveX DLL) wrapping Windows Task Scheduler jobs, triggers, and schedule objects, plus a small `Test` host. Sensitive class/module sources are redacted to `*.example` in this tree. Open `Schedule.vbg` or the `.vbp` files in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** ActiveX DLL, WinForms exe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `TaskScheduler` (`ScheduleCtrl.vbp`) | VB6 | ActiveX DLL | Edanmo's Task Scheduler Class v1.01 |
| `Project2` (`Test/Test.vbp`) | VB6 | WinForms exe | Test host for the scheduler DLL |

## How to open

Open the group or `.vbp` in Visual Basic 6.0 IDE:
- `Schedule.vbg`
- `ScheduleCtrl.vbp`
- `Test/Test.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - Edanmo OLE interfaces (`olelib.tlb`) as referenced by the project

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/schedule`.
Company names in `.vbp` files: Eduardo A. Morcillo.
Third-party attribution: Eduardo A. Morcillo (Edanmo). See `THIRD_PARTY_NOTICES.md`.

## License

Third-party code remains under its original terms (or none, where none were supplied). See `THIRD_PARTY_NOTICES.md`. Do not treat this tree as VaderConsulting original MIT-licensed work.
