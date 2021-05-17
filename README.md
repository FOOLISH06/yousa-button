# 冷鸟按钮 / YOUSA-BUTTON
网址在这里：[**冷鸟按钮**](http://foryousa.icu) 

感谢 [lizi](https://github.com/lonelyion) 的代码，本项目是基于 lizi 的 [fubuki-button](https://github.com/lonelyion/
material-vtuber-button) 修改而来，旨在打造一个 yousa 的语音分享平台，供广大鸟蛋娱乐之用（~~整活？不存在的~~） 
<br><br>
我只是做了一点点的修改工作，加上本人才疏学浅，难免会有一些修改得不到位的地方，还望大家谅解，遇到严重影响体验的bug可以联系我。   
<br>
欢迎大家加入六哥的鸟蛋群（*非官方*）   
<img src="https://cdn.jsdelivr.net/gh/FOOLISH06/yousa-button@master/static/img/鸟蛋群.png">
<br><br>

## TODO
- 修改网页配色，初定为冷鸟的红白配色（需要其他学前端的同学的帮助，本人实在是直男审美）
- 完善网站的音频和链接
- 添加一些 yousa 的图标

## 参与完善本项目
如果你不熟悉GitHub的开发，可以添加六哥的鸟蛋群，将素材上传到群文件，我会不定期更新

### 添加或修改音频

音频文件为mp3格式，码率128Kbps，储存在 `static/voices/` 目录下，对应的URL为 `/voices/` 。

所有的音频信息都存储在 `assets/voices.json` 中，要添加或修改音频，你同样需要修改这个文件中对应的内容。 

如果需要对现有音频进行修改，建议将原音频文件删除，重新命名一个新文件，这样可以避免浏览器缓存问题。  

建议使用 MP3Gain 这类软件将音量标准化为 90 。

### 参与网页开发

本项目使用Vue + NuxtJS + Vuetify框架进行开发，要部署本地开发环境，请先安装最新版的Node与Yarn包管理器。  

1. Fork 并 Clone 代码到本地
2. 进入代码目录，运行 `yarn` 以安装依赖项目
3. 开启本地开发服务器，运行 `yarn dev` ，这将会在 `localhost:3000` 启动，在代码修改过程中，本地开发服务器可以即时反映修改的结果。
4. 要编译可供部署的文件，请运行 `yarn generate` ，这将会在 `dist` 目录下生成可以直接部署到静态网站托管（GitHub Pages等）的文件。 （如果你不准备部署到自己的网站上，不需要做这一步）

## 贡献名单：
开发：  
- GitHub [愚者](https://github.com/FOOLISH06)   

音频：   
- Bilibili [Kaze丶風男](https://space.bilibili.com/97374348/)  
- Bilibili [愚者w](https://space.bilibili.com/499213967)  



## 协议

[MIT License](https://github.com/voosc/fubuki-button/blob/master/LICENSE)

本项目为爱好者作品，和 泠鸢 yousa  官方没有关联

## 支持

### BrowserStack

Proudly using BrowserStack.

[![](https://i.loli.net/2017/09/27/59cbc16b0f8b4.png)](https://www.browserstack.com/)

> **BrowserStack** is a cloud-based cross-browser testing tool that enables developers to test their websites across various browsers on different operating systems and mobile devices, without requiring users to install virtual machines, devices or emulators.

### Vercel

Powered by Vercel.

[![vercel.png](https://i.loli.net/2020/07/18/rPah8FVmqBXL6dj.png)](https://www.vercel.com/?utm_source=oruyanke)

> **​Vercel** is a cloud platform for static sites and Serverless Functions that fits perfectly with your workflow. It enables developers to host Jamstack websites and web services that deploy instantly, scale automatically, and requires no supervision, all with no configuration.


