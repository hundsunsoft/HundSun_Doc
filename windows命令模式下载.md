# windows命令下载
1. 启动powershell
```
start powershell
```
2. 在powershell中我们命令
```
$client = new-object System.Net.WebClient
$client.DownloadFile('http://fe.faisys.com/header_1_0/css/header.min.css?v=201905291726','header.min.css')
$client.DownloadFile('http://jz.faisys.com/css/header.min.css?v=201904031416','header.min.css')
$client.DownloadFile('http://fe.faisys.com/header_1_0/css/header.min.css?v=201905291726','header.min.css_1_0')
$client.DownloadFile('http://jz.faisys.com/css/case.min.css?v=201904031416','case.min.css')
$client.DownloadFile('http://fe.faisys.com/fkService_1_0/css/fk_service.min.css?v=201905151259','fk_service.min.css')
$client.DownloadFile('http://jz.faisys.com/css/mainCss.min.css?v=201904031416','mainCss.min.css')
```