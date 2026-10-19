# Project Gravemind

Halo 2 from Halo: The Master Chief Collection, played outside MCC: a console-style launcher, online
multiplayer for up to 24 players, co-op campaign for up to 6 and more. Free, non-commercial fan project.
This repository only hosts the builds; the source code is not public.

## Getting it

Grab `h2gravemind.zip` from the [latest release](../../releases/latest), unzip it anywhere and run
`h2gravemind.exe`. You need your own Steam copy of Halo: The Master Chief Collection with Halo 2 installed;
no game files come with the download.

Already have it? The launcher checks for new releases when it opens and shows **NEW VERSION** on the
main menu: **UPDATE** downloads, installs and restarts it for you. Your settings stay as they are.

## Versions

Versions look like `0.18.222`. The middle number is the network protocol: players need the same one to
play together. The last number goes up with every build.

## Checking a download

Each file's SHA-256 is listed on its release page. To compare in PowerShell:

```powershell
Get-FileHash .\h2gravemind.zip -Algorithm SHA256
```

## Legal

Project Gravemind is not affiliated with or endorsed by Microsoft, Xbox Game Studios, Halo Studios,
343 Industries, Bungie or Valve. Halo and Halo: The Master Chief Collection are trademarks of the
Microsoft group of companies.
