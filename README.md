# Win98 Command Line Style for BILIBILI Chat

一个模仿 Windows 98 命令行界面风格的 B站直播间弹幕样式。

## 在线预览

👉 [点击这里查看在线预览](https://chil1t.github.io/Win98_bilibilidanmuku_style/)

预览页面提供以下功能：
- 发送各类型测试消息
- 实时预览样式效果
- 模拟真实弹幕场景

## 特性

- 🖥️ 复古的 DOS/Win98 命令行界面风格
- 📝 打字机效果的消息显示
- 🎨 CRT 显示器视觉效果（扫描线、闪烁等）
- 💬 支持各类消息样式（普通消息、礼物、SC、系统通知等）
- 🔤 完整的中文像素字体支持
- 🌗 深色模式适配
- 📱 响应式设计

## 预览效果

- 普通消息：命令行风格的用户发言
- 礼物消息：橙色主题
- SC消息：粉色主题
- 系统消息：暗绿色斜体
- 管理员消息：蓝色主题
- 舰长消息：紫色主题

## 使用方法

1. 在 OBS/直播姬 中添加浏览器源
2. 设置弹幕样式为自定义CSS
3. 复制 `project.css` 中的内容到自定义CSS框中
4. 保存设置即可使用

## 字体说明

样式使用了以下字体：
- VT323：主要英文字体
- Zpix：中文像素字体
- DotGothic16：备选像素字体
- Monospace：降级字体

## 自定义配置

可以通过修改 CSS 变量来自定义样式：
- --cmd-green: 主要文字颜色
- --cmd-dim-green: 暗色文字
- --cmd-yellow: 高亮文字
- --cmd-white: 白色文字
- --cmd-blue: 蓝色文字
- --cmd-bg: 背景色

## License

MIT License

## 作者

设计：Claude&&Chil1T
