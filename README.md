https://github.com/iuiaoin/plugin_tiktok/assets/12285381/54ff8066-eb34-4d61-aea9-f946970ebaf5

# wechat-gptbot TikTok插件

本项目作为 `wechat-gptbot` 插件，可以根据关键字随机回复tiktok视频。

## 安装指南

### 1. 添加插件源
在 `plugins/source.json` 文件中添加以下配置：
```
{
  "keyword_reply": {
    "repo": "https://github.com/lepingzhang/plugin_tiktok.git",
    "desc": "TikTok美女视频"
  }
}
```

### 2. 插件配置
在 `config.json` 文件中添加以下配置：
```
"plugins": [
  {
    "name": "tiktok",
    "command": ["看看美女", "来个妹子"],
  }
]
```

## 感谢
复刻自[plugin_tiktok](https://github.com/iuiaoin/plugin_tiktok)，因为原本的似乎不支持命令列表，让GPT改了一个参数支持命令列表。
