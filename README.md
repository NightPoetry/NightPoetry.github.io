# nightpoetry.github.io

腾狐科技工作室 · 夜诗（NightPoetry）的个人作品站 / 公司官网。

**线上地址：** https://nightpoetry.github.io/

## 结构

| 路径 | 内容 |
|------|------|
| `/` (`index.html`) | 官网首页 —— 作品站（深色霓虹 / 玻璃拟态，纯静态、零外部依赖） |
| `/fascut/` (`fascut/index.html`) | **FasCut**（迅影狐）产品页 + 隐私政策 + 反馈表单。曾错放在根目录，现已迁至此二级路径 |
| `/whenscript/` | **WhenScript** 反应式语言（由独立仓库 `NightPoetry/whenscript` 作为 project page 部署，同域二级路径） |
| `/assets/` | 首页图片资源（FasCut 截图，已压缩） |
| `favicon.svg` | 腾狐 fox 图标 |

## 主要作品

- **FasCut** — 直觉式视频剪辑（macOS，App Store）→ `/fascut/`
- **WhenScript** — 事件驱动的强类型反应式语言 → `/whenscript/`

## 迁移注意（App Store）

FasCut 页面从根目录迁到了 `/fascut/`。Apple 后台此前登记的链接需同步更新：

- 支持网址：`https://nightpoetry.github.io/` → **`https://nightpoetry.github.io/fascut/`**
- 隐私政策：`https://nightpoetry.github.io#privacy` → **`https://nightpoetry.github.io/fascut/#privacy`**

为过渡期兼容，首页对老的 `#privacy` 锚点做了自动转发（`index.html` 头部脚本）。

## 本地预览

纯静态站点，任意静态服务器即可：

```bash
python3 -m http.server 8000
# 打开 http://localhost:8000/
```
