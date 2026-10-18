# HTML Toolbox · 常用 HTML 小工具库

收录日常电商视觉、图片处理和设计工作中的实用 HTML 小工具。**每个功能组一个一级目录，HTML 与 JSON 等配套文件放在一起，根目录只作索引。**

## 工具导航

| 工具 | 常用度 | 简介 | 在线体验 | HTML |
| --- | :---: | --- | --- | --- |
| **图片实时对比工具** · v1.1 | ★★★★★ | 多版本对比、三态差异高亮（常规 / 黑底 / ΔE2000 热力图）、临时热力图缓存 | [体验](https://www.showyourcode.app/share/qglr1umvdox0cy) | [查看](./图片预览与对比/图片实时对比工具.html) |
| **移动端三模式图片预览** | ★★★★★ | 拖拽多张详情图，切换默认、天猫和京东预览方式 | [体验](https://www.showyourcode.app/zh/share/9d248f9e-dd87-4ac8-b366-741d319b6338) | [查看](./图片预览与对比/移动端三模式图片预览.html) |
| **自定义裁切工具 · Slice Studio** | ★★★★★ | 三栏切片工作台、图片批处理、OCR 命名、PNG/JPG/ZIP 导出，支持导入裁切 JSON | / | [查看](./自定义裁切/自定义裁切工具.html) |
| **CSV 编辑器** | ★★★★★ | Excel 式 CSV 编辑、公式转数值、按选中列去重、导出 CSV | / | [查看](./数据表格编辑/CSV编辑器.html) |
| **Markdown 编辑与预览工具** · 标准 CDN | ★★★★☆ | Markdown 编辑、实时预览、目录导航、代码高亮及 Mermaid 图表 | [体验](https://www.showyourcode.app/share/1c80ab11-4f4a-4b47-baf3-425d4df2ee58) | [查看](./Markdown编辑与预览/Markdown预览工具-标准CDN.html) |
| **Markdown 编辑与预览工具** · 国内镜像 CDN | ★★★★☆ | 与标准版功能相同，部分 CDN 地址改用国内镜像，便于国内网络环境尝试 | [体验](https://www.showyourcode.app/share/1c80ab11-4f4a-4b47-baf3-425d4df2ee58) | [查看](./Markdown编辑与预览/Markdown预览工具-国内镜像CDN.html) |
| **色块拼接排版工具** · v2.0 | ★★★☆☆ | 图片横向拼接、按货号前 7/9 位分组、跨组拖拽排序、重叠间距与自定义高度、逐组及批量 PNG 导出 | [体验](https://www.showyourcode.app/share/370f3adc-b938-4057-bf07-714a34acd9b9) | [查看](./图片拼接与排版/色块拼接排版工具-v2.0.html) |
| **色值获取 · 色彩分析 Pro** | ★★☆☆☆ | 拖入多张图片提取 6 色调色板、局部框选取色、色阶增强对比及整体平均色，点击色块复制 HEX | [体验](https://www.showyourcode.app/share/9c90eb54-d8e8-4364-b55f-d21e126c69dd) | [查看](./色彩分析与取色/获取色值.html) |
| **PPT 详情页切片整理** · v4 | ★★☆☆☆ | 批量缩放、底部白边裁切、拖拽排序、重命名及 JPG/ZIP 导出（与自定义裁切独立） | / | [查看](./PPT详情页整理/PPT详情页切片整理.html) |

> **常用度：** 根据日常使用频率人工标注，五星为最常用；不代表工具质量评分。

> 在线体验链接由 ShowYourCode 提供，与 GitHub 源文件**不是自动同步**；使用新版本请以本仓库 HTML 为准。未提供外部体验地址的工具仅列出 GitHub 源文件，不猜测、不虚构在线链接；Markdown 在线体验为两种 CDN 版本共用的参考体验地址，体验页代码不与本仓库自动同步。

> **目录说明：** `自定义裁切/` 只收录自定义裁切 HTML 及其七份 JSON 模板；`PPT详情页整理/` 为另一个独立工具，没有使用这些裁切 JSON。两者互不依赖。目录最多保持一级。

## 自定义裁切 · 配套 JSON 模板

所有模板位于 [自定义裁切目录](./自定义裁切)。打开工具后点击顶部 **「导入配置」**，选择下载的 JSON 文件即可导入。**这些文件是独立配置，并不会仅因为与 HTML 放在同一目录就自动载入。**

| 裁切模板 | 配置文件 |
| --- | --- |
| 详情页裁切 v5 | [详情页裁切-v5.json](./自定义裁切/详情页裁切-v5.json) |
| 优化主图 · 京东 1125 | [优化主图-京东-1125.json](./自定义裁切/优化主图-京东-1125.json) |
| 优化主图 · 京东模板 | [优化主图模板-京东.json](./自定义裁切/优化主图模板-京东.json) |
| 优化主图 · 京东 / 唯品会去重合并 | [优化主图模板-京东唯品会-去重合并.json](./自定义裁切/优化主图模板-京东唯品会-去重合并.json) |
| 优化主图 · 天猫 | [优化主图模板-天猫.json](./自定义裁切/优化主图模板-天猫.json) |
| 优化主图 · 全渠道 | [优化主图-全渠道.json](./自定义裁切/优化主图-全渠道.json) |
| 优化主图 · 唯品会 | [优化主图-唯品会.json](./自定义裁切/优化主图-唯品会.json) |

## 仓库结构

```text
HTML-Toolbox/
├── README.md
├── 图片预览与对比/
│   ├── 图片实时对比工具.html
│   └── 移动端三模式图片预览.html
├── 图片拼接与排版/
│   └── 色块拼接排版工具-v2.0.html
├── 色彩分析与取色/
│   └── 获取色值.html
├── 自定义裁切/
│   ├── 自定义裁切工具.html
│   ├── 详情页裁切-v5.json
│   ├── 优化主图-京东-1125.json
│   ├── 优化主图模板-京东.json
│   ├── 优化主图模板-京东唯品会-去重合并.json
│   ├── 优化主图模板-天猫.json
│   ├── 优化主图-全渠道.json
│   └── 优化主图-唯品会.json
├── PPT详情页整理/
│   └── PPT详情页切片整理.html
├── 数据表格编辑/
│   └── CSV编辑器.html
└── Markdown编辑与预览/
    ├── Markdown预览工具-标准CDN.html
    └── Markdown预览工具-国内镜像CDN.html
```

## Markdown 预览工具 · 版本说明

| 版本 | 依赖说明 |
| --- | --- |
| [标准 CDN 版本](./Markdown编辑与预览/Markdown预览工具-标准CDN.html) | 常用海外 CDN（如 cdnjs、jsDelivr）加载字体、Markdown 渲染及代码高亮相关资源 |
| [国内镜像 CDN 版本](./Markdown编辑与预览/Markdown预览工具-国内镜像CDN.html) | 部分资源使用 BootCDN / Staticfile；Mermaid 仍从 jsDelivr 加载，**不是完全离线版本** |

两版保留原始完整 HTML，不混合代码、不覆盖。可以直接下载后用浏览器打开，但由于脚本资源依赖 CDN，仍需可访问相应资源的网络环境。对 Markdown 预览建议仅加载可信内容。

## 使用与维护

- **在线体验：** 点击导航表中的体验链接，可直接试用已发布的外部体验版。
- **本地运行：** 点击对应 HTML，在 GitHub 页面中选择 **Download raw file** 下载；用现代浏览器打开。
- **配置文件：** 在对应工具目录下载 JSON，通过工具内「导入配置」功能加载。
- **版本管理：** 维持清晰、稳定的工具文件名；后续升级覆盖同一路径，依靠 Git 提交历史追溯版本；新增工具或配套 JSON 只更新同一组目录和根 README。
- **目录约束：** 最多一层功能组目录（`功能组/文件`），不再额外增加 `tools/`、`assets/`、`presets/` 等子目录。
- **外部依赖：** 图片对比使用 Tailwind / Lucide CDN；裁切工作台使用 Bootstrap / JSZip CDN；PPT 切片整理使用 JSZip CDN；色块拼接排版使用 Tailwind / React / Babel CDN；色值获取使用 Color Thief CDN；CSV 编辑器使用 Luckysheet / PapaParse CDN；Markdown 工具使用 Marked / Highlight.js / Mermaid 等 CDN。网络断开时 CDN 样式、图标或 ZIP 功能可能受影响。裁切工具若使用 UMI-OCR，还需本地 OCR HTTP 服务正常运行和浏览器允许访问。

Maintained by [hong87LH](https://github.com/hong87LH).
