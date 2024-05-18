Openresty
=

## (一) 說明

* Openresty 使用 Nginx 與 Lua 語法實現 Load Balancer

## (二) 下載 Openresty 與測試說明

* Windows Download Openresty：[連結](https://openresty.org/en/download.html)
* 下載後解壓縮測試啟動
    - (1) cmd 到 \openresty 目錄下
    - (2) 執行 start nginx.exe 指令
    - (3) 確認是否啟動成功，http://localhost:8080/

## (三) Windows 操作 Openresty 常用指令

* 啟動：start nginx.exe
* 停止：nginx -s stop 或 taskkill /F /IM nginx.exe
* 重啟：nginx -s reload
* 監測：使用 PowerShell 到 logs 目錄下執行 Get-Content "error.log" -Wait