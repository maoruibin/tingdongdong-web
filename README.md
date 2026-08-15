# 听咚咚 TingDongDong

> 流媒体 App 让你租歌，听咚咚让你拥有歌。

极简本地音乐播放器：打开即播、内嵌歌词、冷门格式也安排、听歌日记。无广告、无推荐、断网也能用。多端同步（手机 ⇄ 桌面）开发中。

## 下载

| 平台 | 渠道 | 链接 |
|------|------|------|
| Android | 蒲公英（主渠道） | <https://www.pgyer.com/tingdongdong-android> |
| Android / 桌面版 | GitHub Releases | <https://github.com/maoruibin/tingdongdong-web/releases/latest> |

桌面版（macOS / Windows）将通过 GitHub Releases 发布。

## 本仓库是什么

- **官网落地页**：`index.html`，由 GitHub Pages 托管 → <https://maoruibin.github.io/tingdongdong-web/>
- **安装包分发中心**：Android APK / 桌面安装包挂在 [Releases](https://github.com/maoruibin/tingdongdong-web/releases)
- 客户端核心代码**不开源**（私有备份仓库），不在本仓库

## 本地预览

```bash
python3 -m http.server 8471
# 打开 http://localhost:8471/index.html
```

`preview/` 目录是设计自检截图，不参与页面渲染。
