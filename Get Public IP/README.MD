## Get Public IP

Get's public IP using ifconfig.me website.


```powershell
$pubip = (invoke-webrequest -UseBasicParsing "https://ifconfig.me/ip").content
```

![](screenshot0.png)