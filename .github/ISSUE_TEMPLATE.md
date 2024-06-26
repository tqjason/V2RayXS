---
name: V2RayXS issue 模版
---

请回答下列问题。不按模板发的 issue 将直接被关闭。

0) 如果你没有遇到任何错误和不正常，请在此处回答你想发表的内容：

1) 你正在使用哪个版本的 V2RayXS，你的 macOS 系统版本？

2) 如果你在操作 V2RayXS 的时候遇到程序崩溃/无反应，请描述你的操作，之后在命令行（终端.app）里运行`/Applications/V2RayXS.app/Contents/MacOS/V2RayXS`，重复上述操作直至软件崩溃，把终端里的输出贴到下面指定的地方。

```
在这里贴上终端的输出
```

3) 如果 V2RayXS 没有发生崩溃，但是有一些不正常行为，比如上次勾选了 mux，再次打开，mux 的钩没有了。请描述你遇到的不正常行为。

4) 如果 V2RayXS 一切正常，但网络依然不如你所预料，请首先把 log level 切换到 debug，再次访问你想访问的网站。然后点击 V2RayXS 的 `view current config.json`，将弹出的浏览器内的配置文件粘贴到下面指定的地方，但是隐藏掉ip/端口/id等信息。

```javascript
在这里粘贴配置文件内容
```

然后点击 V2RayXS 的`view log`，把 error.log 中的输出贴到下方：

```
在这里贴上 error.log
```

5) 其他你认为可以帮助开发者和你一起解决问题的信息：
