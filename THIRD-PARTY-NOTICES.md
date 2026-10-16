# 第三方组件与许可声明

本项目包含或引用了以下第三方作品，其权利归各自作者所有。

---

## 1. Bruno（被汉化对象）

- 项目地址：<https://github.com/usebruno/bruno>
- 官方网站：<https://www.usebruno.com/>
- 许可证：**MIT License**
- 版权：Copyright (c) 2022 Anoop M D, Anusree P S and Contributors

Bruno 的下列内容以「词典中的界面短句」或「补丁清单中用于校验与还原的少量原始字节」的形式出现在本项目产物中：

| 出现在哪里 | 内容 | 体量 |
|---|---|---|
| `payload/zh-cn.js` 的 `DICT` 键 | Bruno 界面的英文短句（如 `Send`、`Create Collection`） | 3100+ 条短句 |
| `payload/patch-manifest.json` | `web/index.html` 与 `src/app/menu-template.js` 的原始字节与汉化后字节（base64） | 各约 3.5 KB |

以上内容均在 MIT 许可范围内使用。以下为 Bruno 的 MIT 许可全文：

```
MIT License

Copyright (c) 2022 Anoop M D, Anusree P S and Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

**说明**：Bruno 的付费版本（Bruno Ultimate / Pro / Golden Edition）及其授权校验模块
**并未包含在 Bruno 的开源仓库中**，因此本项目也不包含、不修改、不绕过任何相关内容。
本项目仅对 Bruno 的免费开源核心界面做中文文本替换。

---

## 2. 未包含的其他组件

本项目**不包含**、也**不再分发**以下内容：

- Bruno 的官方安装程序（`bruno_*.exe`）
- Bruno 的官方构建产物（`app.asar`、任何预打包的应用二进制）
- Bruno 的源码副本

这些内容请从 Bruno 官方渠道获取：<https://www.usebruno.com/downloads>

---

## 3. 商标

"Bruno" 名称及相关标识归其权利人所有。本项目在 README 与描述中使用该名称，仅为
**说明本汉化所适用的软件对象**（指示性合理使用），不代表任何形式的官方关联、赞助或背书。

本项目未使用 Bruno 的 Logo 或其他官方视觉标识。
