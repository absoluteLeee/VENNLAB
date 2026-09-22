# VENNLAB

ABio 项目下的本地集合交集与维恩图工具。仓库：`absoluteLeee/VENNLAB`。

## 使用

完整解压后双击 `start.cmd` 或用现代浏览器打开 `Venn.html`。不需要 Python、R、Node.js，也不需要联网安装依赖。

- 支持 2、3、4 个集合，每行一个元素，集合内重复项会去重。
- 左侧输入，中间预览及交集结果，右侧颜色、透明度和字号设置。
- 四集合采用 jvenn 经典布局，显示 15 个互斥交集区域；数字或结果行可查看元素。
- 导出 PNG、SVG、TIFF；PDF 使用浏览器打印窗口另存为 PDF。
- 保存记录保存在当前浏览器的 localStorage，不会随文件夹复制到另一台电脑。

## 离线资源

`fonts/` 包含标题字体、思源黑体及 DejaVu 回退字体；`lib/` 包含 jQuery、jvenn、canvas2svg。保持目录结构完整。`package.json` 仅用于开发追踪依赖，普通使用无需 npm install。

字体文件随工具提供不等于导出的 SVG 内嵌字体；在其他电脑打开 SVG 时仍可能发生字体替换。需要固定外观可使用 PNG/TIFF。

## 发布状态

这是源码分发版本。项目许可证待作者决定；第三方许可见 `THIRD_PARTY_NOTICES.md`。不要将 ABio 的非商业许可直接覆盖到 jvenn。

## 使用说明

详见 [中文使用说明](使用说明.md)。

所属项目：[ABio](https://github.com/absoluteLeee/ABio)。
