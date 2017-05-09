This repository is sample code for ASP.NET Core & Angular 4 (Angular 2) SPA.  
Use the Visual Studio 2017 to development.  

# ASP.NET Core + Angular 4 教學 - Redis Session

本篇將介紹 ASP.NET Core 用 Redis Cache 存放 Session，避免 Web Application 重啟後，用戶要重新登入。  

Blog：  
[ASP.NET Core + Angular 4 教學 - Captcha](https://blog.johnwu.cc/article/asp-net-core-angular-4-%E6%95%99%E5%AD%B8-captcha.html)

程式碼延續之前範例：  
[ASP.NET Core + Angular 4 教學 - Captcha](/article/asp-net-core-angular-4-教學-captcha.html)  

## 說明

安裝軟體的部分我就沒有詳細介紹，以下是我使用到的工具跟語言。

開發工具：
1. Visual Studio 2017 (可使用其他版，只要有支援 ASP.NET Core 開發就可以。)
2. Nodejs 6.9.x 以上版本 及 npm 3 以上版本

開發語言：
1. .NET Core 使用 C#
2. Angular 4 使用 TypeScript

下載範例後記得在專案目錄安裝 npm package

``` batch
npm install
```
