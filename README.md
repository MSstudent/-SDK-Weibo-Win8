新浪微博Win8官方SDK
===============

RELEASE NOTES

>V1.0包含如下功能:   
集成授权页面，支持OAuth2.0授权。    
对微博常用接口封装，以方便调用。    
支持对大部分微博接口访问。    


###概述：
>新浪微博 Windows  8 平台官方 SDK 包提供给第三方开发者 OAuth 授权登录及基本 Open API 的请求，大大
简化了第三方集成微博相关服务的难度。本 SDK采用 Windows Rumtime Component  形式发布， 支持 Windows Store App 
应用程序开发，可以使用 C#/VB/C++/JavaScript&Html5 语言调用本 SDK 提供的相应功能。   
集成的 OPEN API 版本为 V2 版，以后会随着 OPEN API 的版本升级更新的微博 SDK
包。

###授权模式：
>OAuth 2.0

###申请API Key：
>请登陆 <http://open.weibo.com/development/mobile> ,创建应用并获取相关API Key，只有进行申请后才能正常使用SDK


###SDK 使用说明：
>1.  环境安装
>安装 Windows 8 Store App 相关开发环境。


>2.  引入 SDK 所需文件   

>C#/VB、JavaScript&Html5 项目    
>>选中项目，右键 References->Add Reference->Browse...，在打开文件选择
窗口找到 Release 目录下的 RestSharp.winmd 和 WeiboSDKForWinRT.winmd
文件，点击 Add 将它们添加到项目引用中去。  

>C++/CX 项目   
>>选中项目，右键 项目属性 ->Common Properties->Framework and 
References，点击 Add  new  Reference，在打开文件选择窗口找到 Release
目录下的 RestSharp.winmd 和 WeiboSDKForWinRT.winmd 文件，点击 Add
将它们添加到项目引用中去。   

###SDK使用参考：
>请见该仓库的 微博Windows 8平台SDK使用说明.pdf 文件  
>或在此下载 <http://weibowinrtsdk.codeplex.com/downloads/get/636457>


