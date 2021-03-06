# 浏览器兼容性
## 概述
不同浏览器对 Web 标准的支持不同。导致同样的代码在不同的浏览器上**可能**会产生不同的效果。    

因此，我们有时需要针对浏览器写一些代码来让浏览器的呈现保持某种程度上的一致。    


某种程度指：在流程之类的体验上一致的（渐进增强），在一些细节方面，可以部分浏览器不一样（优雅降级）。

## 浏览器对特性的支持性
可以在[Can I use](http://caniuse.com/)上在线查看。    
也可以用类库 Modernizr，以及 CSS的[@supports](http://www.qianduan.net/css-at-supports/)特性.

## 对不同浏览器进行不同的处理
见[css-hack](css-hack.md)

## 常见浏览器bug及处理
见[常见浏览器bug及处理](css-bugs.md)

## 资源
* [腾讯浏览器常见问题](http://x5.tencent.com/guide?id=2001) 微信 6.X 以上的内核都是用的腾讯浏览器。