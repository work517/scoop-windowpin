# WindowPin — Scoop bucket

Sticky notes that lock to a specific window and move with it. <https://windowpin.com>

```powershell
scoop bucket add windowpin https://github.com/work517/scoop-windowpin
scoop install windowpin
```

Installing this way never goes through a browser, so neither the download warning nor the
Windows SmartScreen dialog appears. Scoop verifies the SHA-256 for you.

Notes live in `%APPDATA%\WindowPin` and survive `scoop uninstall` — delete that folder
yourself if you want nothing left behind.

Contact: projectteamforyou@gmail.com
