# LMU Rewind

Downloads of **LMU Rewind**, a Windows app for Le Mans Ultimate: save
checkpoints on track and put your car back at any of them to practice a corner
or section again.

What it does, what it needs and its limits: **[LMU Rewind on Marzili Labs](https://marzili-labs.dev/en/software/lmu-rewind/)**.

This repository holds releases only, not source code.

## Download and install

1. Open the [latest release](https://github.com/nintschger/LMU-Rewind-releases/releases/latest)
   and download `LMU-Rewind-<version>-win-x64.zip` under **Assets**.
2. Right-click the ZIP, choose **Extract All**, open the extracted folder and
   start **`LMU-Rewind.exe`**. There is no installer; keep the folder together.
3. The package is unsigned, so Windows SmartScreen may warn on first launch.
   Choose **More info → Run anyway** if you trust this download. You can check it
   first: compare `Get-FileHash -Algorithm SHA256 .\LMU-Rewind-<version>-win-x64.zip`
   with `SHA256SUMS.txt` from the same release.

Checkpoints work only in LMU's **Offline** mode, in a **Practice** session, with
the game started **without Easy Anti-Cheat**. Read the release notes for the
known issues of each version before you use it.

## Report a problem

Open an [issue](https://github.com/nintschger/LMU-Rewind-releases/issues/new/choose)
with your LMU Rewind version, LMU version, car, track, the exact message and
the steps that reproduce it. Issues are public: anything you attach, such as a
diagnostics file exported under **Activity**, can be read by anyone.

LMU Rewind is an independent project and is not affiliated with Le Mans
Ultimate. It is released under the [MIT license](LICENSE).
