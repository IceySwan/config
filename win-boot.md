# Win boot

## Win-get

Official website: https://winstall.app/

```
winget install --id=Git.Git  -e
winget install --id=Google.Chrome  -e
winget install --id=Mozilla.Firefox  -e
winget install --id=ClashVergeRev.ClashVergeRev  -e
winget install --id=Microsoft.VisualStudioCode  -e
winget install --id=JetBrains.PyCharm  -e
winget install --id=Telegram.TelegramDesktop  -e
winget install --id=CrystalIDEASoftware.UninstallTool  -e
winget install --id=CollapseLauncher.Collapse  -e
winget install --id=MiKTeX.MiKTeX  -e
winget install --id=Valve.Steam  -e
winget install --id=Hugo.Hugo.Extended  -e
winget install --id=monkeyWie.Gopeed  -e
winget install --id=mulaRahul.Keyviz  -e
winget install --id=FilesCommunity.Files  -e
winget install --id=Daum.PotPlayer  -e
winget install --id=JohnMacFarlane.Pandoc  -e
winget install --id=PixPin.PixPin  -e
```

## Powershell

office

```
irm https://get.activated.win | iex
```

win 激活

```
irm https://massgrave.dev/get | iex
```

终端代理

```
set http_proxy=http://127.0.0.1:7897
set https_proxy=http://127.0.0.1:7897

set http_proxy=http://127.0.0.1:6952
set https_proxy=http://127.0.0.1:6952
```

MHY

```
[Net.ServicePointManager]::SecurityProtocol = [Net.ServicePointManager]::SecurityProtocol -bor [Net.SecurityProtocolType]::Tls12; Invoke-Expression (New-Object Net.WebClient).DownloadString("https://gist.githubusercontent.com/Star-Rail-Station/2512df54c4f35d399cc9abbde665e8f0/raw/get_warp_link_cn.ps1?cachebust=srs")
```

