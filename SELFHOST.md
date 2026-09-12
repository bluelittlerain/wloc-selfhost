# WLOC 独立个人存档

原项目为 [Yu9191/wloc](https://github.com/Yu9191/wloc)，目前已删除或不再公开可访问（2026-09-11 GitHub API 返回 404）。本仓库用于 Quantumult X 个人自托管，保留原作者及贡献者署名和原版 AGPL-3.0 LICENSE，不表示代码由存档者原创。

## 恢复依据

- 采用的最后可确认原版 commit：`529fcd841952571e79f40faf2d3e0ef90a7bdfa6`。
- 原提交时间：2026-09-04 08:20:03 UTC；原 tree：`0463814a3fbb2665efde8255a8a76d5a73561c32`。
- 文件来源：[SkywardLab/wloc 固定提交](https://github.com/SkywardLab/wloc/tree/529fcd841952571e79f40faf2d3e0ef90a7bdfa6)；GitHub API 确认它属于 Yu9191/wloc 的 fork network。
- [2026-09-07 15:55:31 UTC 的原仓库网页归档](https://web.archive.org/web/20260907155531/https://github.com/Yu9191/wloc)记录 main 的完整 SHA 与上述一致；WongAlice/wloc、sharedforks/wloc 也保存同一提交。
- 可信度高：这是已找到且能独立交叉验证的最后原版快照；无法证明删除瞬间没有更晚但未留存的提交。

本仓库此前使用 hankinsus/wloc 镜像快照。此次以原版的全部 25 个跟踪文件恢复，移除该原版快照中已不存在的单文件 Worker；不合入或恢复任何上游 Git 历史。现有个人 root commit 保留，本次仅正常新增恢复提交，不自动同步上游。

## 自托管最小改动

原版源码、UI、默认参数、快捷指令、第三方接口、作者信息及许可证均以所选 commit 原样保存。修改仅限 README 和原版模块中的 GitHub Raw 地址，以及 README 对应的克隆/Cloudflare 部署资源地址；克隆命令显式保留原目录名 wloc。除此之外只增加本维护说明。原项目主页、issue/PR 和贡献者链接作为来源说明保留。

- QuanX 远程重写资源：https://raw.githubusercontent.com/bluelittlerain/wloc-selfhost/main/modules/wloc.conf
- 核心脚本：https://raw.githubusercontent.com/bluelittlerain/wloc-selfhost/main/dist/wloc.js
- 设置脚本：https://raw.githubusercontent.com/bluelittlerain/wloc-selfhost/main/dist/wloc-settings.js

订阅 URL 与此前相同，Quantumult X 刷新远程重写资源与脚本缓存即可加载恢复后的原版配置。原版扩展 MITM 主机名、证书要求与使用限制见 README，未对手机端做实测。

原版公共选点页面、`wloc-spoofer.wloc.workers.dev` 解析服务、Apple/地图接口、Leaflet CDN、iCloud 快捷指令仍为第三方依赖；此迁移没有自行部署 Cloudflare，也没有改写快捷指令内部内容。原 README 对 iOS 27 beta 6 起的 MITM 限制说明原样保留。
