# EB I 百科全书 · 在线更新兜底仓库

本仓库仅作为 Android 版《EB I 百科全书》在线更新的**兜底源**，主链路在 Gitee：https://gitee.com/ksaMask/eb1-encyclopedia

## 文件

| 文件 | 大小 | SHA-256 |
|---|---|---|
| `encyclopedia.html` | 60284646 字节 | `86b16ba420a56ce3c1116673078c0ec7b7bc41ebdaf219f639f5280acf0ec484` |

## 为什么需要它

Gitee 对 57MB 大文件的 `/raw/` 请求返回 403，APP 主下载源走 Gitee 发行版附件；本仓配合镜像（`https://gh-proxy.com/`）作为第二条下载路径。

> 更新内容时请同步替换本文件，并保证字节数与 SHA-256 与 Gitee 侧 `version.json` 完全一致。
