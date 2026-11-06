# Arka Glycan releases

Downloads of [Arka Glycan](https://arkaglycan.com), software for identifying glycans in
released-glycan LC-MS/MS data (Thermo .raw, Bruker timsTOF .d and mzML), on your own computer.

**Arka Glycan is in an invite-only beta.** Each release lists its files under
[Releases](../../releases). Without a licence key the app runs as a 30-day trial; beta labs
receive a key with their invitation.

| File | For |
|---|---|
| `Arka-Glycan-<version>-macos-arm64.zip` | macOS 12 or later on Apple Silicon (M1 or newer) |
| `Arka-Glycan-<version>-Setup.exe` | Windows 10 or 11, 64-bit |
| `SHA256SUMS.txt` | checksums to confirm a download is complete and unaltered |

## Check a download

macOS: `shasum -a 256 Arka-Glycan-*-macos-arm64.zip`
Windows (PowerShell): `Get-FileHash Arka-Glycan-*-Setup.exe`

Compare the result with the line for that file in `SHA256SUMS.txt`.

## First start

The beta builds are not yet code-signed, so your computer warns you once.

- **macOS:** unzip, move Arka Glycan to Applications and open it. When macOS says it was not
  opened, click Done, then open System Settings > Privacy & Security and click **Open Anyway**.
- **Windows:** run the installer; if "Windows protected your PC" appears, click **More info**,
  then **Run anyway**.

The full user guide is in the app (Help) and at https://arkaglycan.com/user-guide.html.

Research use only; not for diagnostic or clinical use.

&copy; 2026 Vaibhav Singh. All rights reserved. The downloads are licensed, not sold; see the
Terms at https://arkaglycan.com/terms.html.
