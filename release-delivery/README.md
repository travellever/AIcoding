# 展区布局：文档与完整原型交付

## 新增：PDF图文教程HTML重排版（全英文）

[下载独立HTML教程](python-tutorial.html) · [下载教程压缩包](python-tutorial-html.zip) · [查看说明与预览](python-tutorial-guide.md)

教程首页与阅读界面已全部改为英文，包含全部内嵌图片，下载后用浏览器打开即可，无需安装环境。

## 新增：v2全功能浏览器原型（19个页面）

**推荐下载 [完整浏览器原型压缩包](exhibition-full-prototype-v2.zip)**。

点击文件后选择 **Download raw file**（向下箭头），保存到本地电脑，完整解压，然后双击：

```
exhibition-full-prototype-v2/index.html
```

无需安装Python、Node或数据库，无需连接网络。请使用本地Chrome、Edge或Firefox，不要在压缩软件的预览窗口中运行。

- [只下载单文件交互原型HTML](full-prototype.html)：也可单独保存为HTML，再由浏览器打开。
- [查看使用说明与19页功能清单](full-prototype-guide.md)
- [查看原型首页截图](full-prototype-preview.png)
- 完整包内的 `screenshots.html` 为19页原型图册；`screenshots/`包含完整截图，`src/`包含源代码。

包括：工作概览、届次展期、展厅、空间容量、展区题材、需求、数据导入、规则、生成任务、方案管理、图形编辑、历史比对、统计、同步、审批发布、导出、审计、权限设置与功能导航。

可以实际操作表单、读取CSV、配置规则、生成模拟方案、拖拽/拆分/合并/交换、锁定重排、版本撤销、演示审批、下载SVG/PNG/JSON/CSV/说明以及打印PDF。修改保存在当前浏览器，可用工作区JSON备份。

所有数据同步、组织归属、审核发布及浏览器生成均为明确标注的离线演示。真实容量、消防与几何仍需审核，不能将示意图当作批准的施工布局。

## 原版：需求文档、量化规则与Python求解原型

[下载原版完整交付包](exhibition-delivery.zip)。其中包括Word设计稿、Excel规则表、原始资料、Python原型和三期真实求解验证。

## 下载遇到困难

请先登录有权访问该仓库的GitHub账号。GitHub不会在线预览zip或执行HTML：用文件右上角的 **Download raw file** 保存到电脑即可。也可从本分支选择 **Code → Download ZIP** 获取所有交付文件，再解压其中的原型包。
