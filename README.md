# DeepSeek Harness 桌面版 · 安装与使用教程

安装、注册、充值、卸载、常见问题都写清楚了，按顺序做一遍就能用。分 **Windows** 和 **macOS** 两套，内容大部分相同，只有安装、托盘 / 菜单栏、数据位置、卸载这几块不一样。

## 从哪里看

| 形式 | 适合 | 文件 |
| --- | --- | --- |
| **网页版（推荐）** | 发给别人看，手机也能看，左侧可一键切换 Windows / macOS | [`index.html`](index.html) |
| Windows 版 Markdown | 在 GitHub 上直接读 | [`DeepSeek-Harness-教程.md`](DeepSeek-Harness-教程.md) |
| macOS 版 Markdown | 在 GitHub 上直接读 | [`DeepSeek-Harness-教程-macOS.md`](DeepSeek-Harness-教程-macOS.md) |

网页版会**自动判断你用的是哪个系统**，并把选择记在浏览器里；也可以直接用链接指定：

- `index.html?os=win`
- `index.html?os=mac`

## 目录结构

```text
index.html                       网页版（唯一入口，含系统切换）
DeepSeek-Harness-教程.md           Windows 版正文
DeepSeek-Harness-教程-macOS.md     macOS 版正文
img/                              截图：Windows 专属 + 两平台共用的界面图
img/mac/                          macOS 专属截图（清单见 img/mac/README.md）
```

## 维护说明

- **公共章节只写一次**：第 0、4、5、6、9、10 节两平台通用，改文案只改 `index.html` 里那份。
- **平台差异靠标记**：在 `index.html` 里给元素加 `data-os="win"` 或 `data-os="mac"`，页面会按当前选择的系统显示其中一套，另一套隐藏。
- **加新截图**：Windows 图放 `img/`，文件名前缀是正文里的「截图 NN」编号；Mac 图放 `img/mac/`，前缀是「Mac 截图 N」编号。图片缺失时页面会自动显示占位框，标出该放哪个文件名。

## 待办

- **设置引导的截图只留了 4 张**（截图 08–11）：原来的 `09-引导2.png` 跟 `10-引导3-充值.png` 是同一张图（都是「准备可用额度」那屏），已删掉重复项，编号整体前移（现在是 01–20 连续），图注也不再写「N／5」，只按内容描述。要补拍别的那屏，插到 `08-引导-开始设置.png` 之后并把后面编号顺延即可。

---

本教程按 DeepSeek Harness 0.2.1-rc.3 编写 · 预览版界面可能随版本调整，按钮文字以实际为准
