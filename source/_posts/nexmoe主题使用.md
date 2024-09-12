---
title: NexMoe主题使用
---
## 去除外部社交链接
需要将带有- 的部分全部删除
```javascript
    - name: social
      enable: true
      options:
        social:
            QQ群:
                - https://jq.qq.com/?_wv=1027&k=5CfKHun
                - icon-QQ
                - rgb(249, 174, 8)
                - rgba(249, 174, 8, .1)
            哔哩哔哩:
                - https://space.bilibili.com/20238211
                - icon-bilibili
                - rgb(231, 106, 141)
                - rgba(231, 106, 141, .1)
            GitHub:
                - https://github.com/nexmoe/
                - icon-github
                - rgb(25, 23, 23)
                - rgba(25, 23, 23, .1)
            知乎:
                - https://www.zhihu.com/people/nexmoe
                - icon-zhihu
                - rgb(30, 136, 229)
                - rgba(30, 136, 229, .1)
            Twitter:
                - https://twitter.com/nexmoe
                - icon-twitter
                - rgb(59, 151, 239)
                - rgba(59, 151, 239, .1)
            RSS:
                - https://nexmoe.com/atom.xml
                - icon-rss
                - rgb(247, 132, 34)
                - rgba(247, 132, 34, .1)

```
## 去除文章底部的链接部分
```javascript

copyTip: "著作权归作者所有。\n商业转载请联系作者获得授权，非商业转载请注明出处。\n来源：%url" # 自定义复制版权文案,使用 %url 代替当前页面URL, 修改为false禁用

slotHead: | 
  <!-- Global site tag (gtag.js) - Google Analytics -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-4D4ZJ9G024"></script>
  <script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag("js", new Date());

    gtag("config", "G-4D4ZJ9G024");
  </script>

slotFooter: | 
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-2058306854838448" crossorigin="anonymous"></script>

# 自定义侧边栏尾部内容
slotSidebar: |
  <br><a target="_blank" href="https://beian.miit.gov.cn/">鄂ICP备2020018486号</a>
  <br><a target="_blank" href="https://www.upyun.com/?utm_source=lianmeng&utm_medium=referral">
  <img src="https://i.dawnlab.me/c0268c1e6cfd0863d6ba35be1575941a.png" width="150px"></a>

# 评论框插槽
slotComment: | 
  请在你的配置文件中设置 slotComment

slotCopyright: | 
  <strong>版权声明：</strong>本文采用 <a href="https://creativecommons.org/licenses/by-nc-sa/3.0/cn/deed.zh" target="_blank">CC BY-NC-SA 3.0 CN</a> 协议进行许可

slotArticleEnd: | 
  <p><img src="https://i.dawnlab.me/53a8c7cf3ad77a0f0a456ce2c6afe88a.png" loading="lazy"></p>
```
#### 自定义侧边栏尾部内容部分显示
slotSidebar: |
  <br><a target="_blank" href="https://beian.miit.gov.cn/">鄂ICP备2020018486号</a>
  <br><a target="_blank" href="https://www.upyun.com/?utm_source=lianmeng&utm_medium=referral">
  <img src="https://i.dawnlab.me/c0268c1e6cfd0863d6ba35be1575941a.png" width="150px"></a>

#### slotArticleEnd部分显示
slotArticleEnd: | 
  <p><img src="https://i.dawnlab.me/53a8c7cf3ad77a0f0a456ce2c6afe88a.png" loading="lazy"></p>
