# Scoop bucket for dynooh apps

[Scoop](https://scoop.sh/) bucket for the free Windows tools from [apps.dynooh.com](https://apps.dynooh.com/).

```powershell
scoop bucket add dynooh https://github.com/Kwisso911/scoop-dynooh
scoop install dynooh/dynooh-minipixels
scoop install dynooh/dynooh-sitemanager
```

| App | Description |
| --- | --- |
| [Dynooh MiniPixels](https://apps.dynooh.com/minipixels/) | Extremely lightweight image, audio and video viewer with rulers, guides, pixel grid and codec info |
| [Dynooh SiteManager](https://apps.dynooh.com/sitemanager/) | Lightning-fast, lightweight FTP site manager: sites, sync, editor, Git and logins in one place |

Both apps are portable, code-signed and open source (MIT). They need the Microsoft Edge WebView2 Runtime, which is preinstalled on current Windows 10 and 11.

Update with `scoop update dynooh-minipixels dynooh-sitemanager`.
