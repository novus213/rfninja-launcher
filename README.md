*[Français](README.fr.md) · **English***

# N.I.N.J.A — Rising Force Online

The server's official launcher.

## Installing

1. Download **`RFNinja-setup.zip`** from the [Releases](../../releases/latest) section.
2. Extract it wherever you want the game installed — allow **9 GB** of free space.
   Avoid `C:\Program Files`: Windows restricts writing there, and the game would
   no longer be able to update itself.
3. Run **`RFNinja.exe`**. Windows will ask for permission: that's normal, the
   game requires administrator rights.

The client (about 3.6 GB) downloads automatically, then the required components
(Visual C++, DirectX) are installed once. If the download is interrupted, just
run `RFNinja.exe` again: it picks up where it left off.

## ⚠️ If the game won't start: your antivirus

The game uses anti-cheat protection, and many antivirus programs block it
because its behaviour looks like that of malicious software.

If you see:

> The application was unable to start correctly (0xc0000142)

it is almost always the antivirus. **Add the game folder to your antivirus
exclusions**, then start again.

With Windows Defender: *Windows Security → Virus & threat protection → Manage
settings → Exclusions → Add an exclusion → Folder*.

## Afterwards

`RFNinja.exe` is also the launcher: run it every time you play. It checks for
updates and applies them before connecting.

## If something goes wrong

- **Windows or your browser flags the file**: the launcher is not digitally
  signed, which is enough to trigger a warning. You can check the SHA-256
  fingerprint published with each release.
- **The download won't start**: make sure `RFNinja.exe` isn't blocked by your
  antivirus or firewall — it needs internet access to install and update the game.
- **Windows N or KN edition**: install Microsoft's *Media Feature Pack*, which
  the game needs for sound.
- **The game still won't start**: delete `Redist\.installed` in the game folder
  and start again — the components will be reinstalled.

## Reporting a problem

Found a bug, or have an idea? Open an [issue](../../issues/new/choose). Please
describe what you saw and how to run into it again — a screenshot is often worth
more than a long explanation.

Recent changes are listed in the [changelog](CHANGELOG.md).

---

This launcher uses [Qt](https://www.qt.io/) 6.6.1, distributed under the LGPL v3
licence. The Qt libraries are provided as-is and can be replaced by the user.
