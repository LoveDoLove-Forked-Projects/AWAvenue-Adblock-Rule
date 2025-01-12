<div align="left">
<a href="/README.md">中文</a>&nbsp;|&nbsp;
<a href="/assets/README_en-US.md">English</a> &nbsp;|&nbsp;
<a href="/assets/README_Update.md">更新日志</a> 
</div>


<h1 align="center">-AWAvenue 秋风广告规则 -</h1>

<p align="center">
   <img src="https://img.jsdelivr.com/raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/assets/assets.png">
</p>
<p align="center">
 <img src="https://img.shields.io/github/stars/TG-Twilight/AWAvenue-Ads-Rule?style=for-the-badge&colorA=FFEBEB&colorB=FFD9DC&logo=github&logoColor=black">
  <a href="https://t.me/AWAvenueAdsRule">
    <img src="https://img.shields.io/badge/dynamic/json?style=for-the-badge&colorA=DAE9FC&colorB=056DE8&label=%E9%A2%91%E9%81%93&logo=telegram&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dtelegram%26queryKey%3DAWAvenueAdsRule" alt="Telegram">
  </a>
  <a href="https://t.me/AWAvenueAdsChat">
    <img src="https://img.shields.io/badge/dynamic/json?style=for-the-badge&colorA=DAE9FC&colorB=056DE8&label=%E7%BE%A4%E8%81%8A&logo=telegram&query=%24.data.totalSubs&url=https%3A%2F%2Fapi.spencerwoo.com%2Fsubstats%2F%3Fsource%3Dtelegram%26queryKey%3DAWAvenueAdsChat" alt="Telegram">
  </a>
</p>


<p align="center"><b>干掉所有无良广告<br>Eliminate All Malicious Ads</b></p>

## 🍁关于此广告规则 | About

开源社区中最优秀的广告过滤器列表之一，实现了最优秀的广告拦截、隐私保护和流量节省。支持各种常见的网络层广告拦截工具和代理工具等¹，与其它动辄成千上万条的广告规则相比，秋风广告规则有着极致的体积控制、超高的命中率和极低的硬件要求。

订阅本规则后，您明显可以感受到烦人的摇一摇广告不见了，订阅号列表和文中文末的广告流无法加载，自动播放的广告视频直接绝迹，电视盒子/智能电视的开机广告消失，同时手机的剩余空间也多了一些（因为阻止了广告文件的下发）

相较于其它去广告的手段，这种从网络层面过滤的方式成本低、使用方便快捷、受益范围广(例如路由器部署)，您无需对每个有需求的app进行单独设置，在无感过滤的同时不影响您正常使用原有的app。

*截止2024年11月，我们可以拦截提瓦特大陆现有九成以上的广告sdk。*

### *如果您对本规则的内容有意见或建议，在提交issue/进群反馈前，请您务必查看我们的[常见问题](https://awavenue.top/Knowledge.html#%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98-%E4%B8%8E%E7%AD%94%E7%96%91)部分，这些内容也许可以解决您的一些疑问。*

---

## 🍁工作原理 | Work Principle

使用Adblock语法，从网络层面对抗(拦截)Android应用中的各种流氓广告SDK，阻止其加载，从而达到去广告的目的。<br />

---

## 🍁订阅规则 | Subscription Rules

适用于AdGuard Home、AdGuard、AdGuard DNS 等支持Adblock语法广告过滤工具的规则

- [Github订阅地址](https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt)
- [天命CFCDN反代订阅地址](https://github.tmby.shop/https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt)
- [jsDelivr(gcore)反代订阅地址](https://gcore.jsdelivr.net/gh/TG-Twilight/AWAvenue-Ads-Rule@main/AWAvenue-Ads-Rule.txt)
- [ghproxy-gci反代订阅地址](https://ghp.ci/https://raw.githubusercontent.com/TG-Twilight/AWAvenue-Ads-Rule/main/AWAvenue-Ads-Rule.txt)

其他格式见[官方网站-订阅规则](https://awavenue.top/Sub.html)

*¹截止2024年7月，我们官方支持的工具/格式有：
AdGuard Home、ClashMeta、QuantumultX、Surge、hosts格式、AdGuard DNS、Surfboard、Singbox、AdClose、AdGuard、大圣净化、广告屏蔽大师Plus+、DNS去广告。*

 *若您在订阅本广告规则后，发现应用内流氓广告sdk仍在正常展示广告/出现误杀，欢迎反馈！*

---

## 🍁如何使用 | How to use
请查看我们的[官方教程](https://awavenue.top/Knowledge.html)

个人项目，随缘维护更新，欢迎issues和Pr。   [😀加入秋風がく山道](https://t.me/AWAvenueAdsChat)。

---

<details>
  <summary>推荐的广告过滤工具</summary>

- [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome)    *安装在路由器，广告过滤工具较为理想的工作位置*，目前，秋风广告规则已加入AdGuard官方列表，你可以直接在 “从列表中选择” 订阅！

- [AdGuard](https://adguard.com/)    *多端使用，支持Android、Windows、Mac、iOS*

- [AdClose（Xposed module）](https://t.me/AdClose)    *Xposed模块，可以通过hook拦截常见广告，内置秋风广告规则，感谢@zjyzip*

- [AdGuard Home For Magisk](https://github.com/twoone-3/AdGuardHomeForMagisk)   *AdGuard Home的Magisk版本*

- [AdGuard DNS](https://adguard-dns.io/en/welcome.html)    *直接使用自定义的DNS服务器，目前，秋风广告规则已加入AdGuard官方列表，你可以直接在AdGuard DNS Filters中订阅！*

- [OpenWrt AutoUpdateHosts](https://github.com/Aethersailor/OpenWrt-AutoUpdateHosts)    *在 OpenWrt 下实现定时自动合并广告拦截规则以及其他加速规则至 hosts 文件，并自动重启 OpenClash 和 Dnsmasq，无需套娃其他插件即可利用 Dnsmasq 实现去广告以及 GitHub 加速功能*

</details>

---

## 🍁赞助商 | Special sponsors

[Stay浏览器 - 无核轻量,专注于提升本身浏览体验的浏览器](https://play.google.com/store/apps/details?id=com.dajiu.stay)

[倾城极速 - 畅游世界，高速互联](https://panel.qqcjs.top/#/register?code=prbbRzx9)

---

## 🍁贡献者 | Contributors

<p align="left"><a href="https://github.com/TG-Twilight/AWAvenue-Ads-Rule/graphs/contributors"><img src="https://contrib.rocks/image?repo=TG-Twilight/AWAvenue-Ads-Rule&max=50" /></a></p>

---

## Star History

[![Stargazers over time](https://starchart.cc/TG-Twilight/AWAvenue-Ads-Rule.svg?variant=adaptive)](https://starchart.cc/TG-Twilight/AWAvenue-Ads-Rule)

---

### ***保持互联网清洁！***

---

[![https://gafam.info](https://ptrace.gafam.info/unofficial/img/color/lqdn-gafam-poster-zh-color-5x1-2560x.png)](https://gafam.info)

---
![:访问数](https://moe-counter.glitch.me/get/@TG-Twiligh?theme=gelbooru)
2024年6月 开始统计......
---

> [@Github](https://github.com/TG-Twilight/AWAvenue-Ads-Rule) · [@Telegram Channel](https://t.me/AWAvenueAdsRule) · [@Telegram Group](https://t.me/AWAvenueAdsChat) · [Official WebSite](https://awavenue.top/)
