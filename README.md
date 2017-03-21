# API_NetCore #

## 認識.NetCore ##
* 彈性部屬
* 跨平台
* CLI 工具
* 相容性
* 開發的原始碼
* 由微軟提供技術支援

## 平台要件 ##
* .Net執行環境
  查看版本: cmd> `dotnet --info`
* 一組框架函式庫(元件)
  查看版本:cmd > `dotnet`
* 一組SDK工具與語言邊義氣
* 應用程式宿主(app host):dotnet

## CLI ##
* 列出所有內建的範本:
  `dotnet new -l`
* 安裝專案範本:
  `dotnet new --install Microsoft.AspNetCore.SpaTemplates::*`
* 建立新專案 ( new ):
  `dotnet new webapi -n MyWebAPI`
* 安裝相依套件 ( restore ):
  `dotnet restore`
* 建置專案 ( build ):
  `dotnet build`
* 執行專案 ( run ):
  `dotnet run`

* IIS 上 架Core 站台
  https://docs.microsoft.com/en-us/aspnet/core/publishing/iis

  
