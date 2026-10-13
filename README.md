# Teal VPN Scoop bucket

Install [Teal VPN](https://tealvpn.com/windows) on Windows 10 and 11 (Intel, AMD and ARM) with [Scoop](https://scoop.sh):

```powershell
scoop bucket add tealvpn https://github.com/tealvpn/scoop-bucket
scoop install teal-vpn
```

Update: `scoop update teal-vpn`. Remove: `scoop uninstall teal-vpn`.

The manifest downloads the same signed setup as the download button on [tealvpn.com/windows](https://tealvpn.com/windows)
(GitHub release of that version, SHA-256 pinned) and runs it silently; Teal VPN installs system-wide (service + driver), so
Windows asks for admin once. Also on winget (`winget install Fxolio.TealVPN`) and Chocolatey (`choco install teal-vpn`).

Teal VPN is free with 500 MB a day, no card and no ads; Teal Pro adds unlimited data and every location. Made by Fxolio LLC.
