# GlowCam (颜光)

📸 一款为现代女性设计的智能美图工具，让每一张照片都自然发光。遵循 MIT 协议开源，欢迎贡献！

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## ✨ 功能特性

- **自然美颜算法**：智能识别面部特征，保留原生肤质细节
- **光影调节引擎**：支持动态光效叠加（柔光/晨光/霓虹光）
- **AI 风格滤镜**：10+ 独家滤镜（如「蜜桃氧气」「冷雾银」）
- **一键导出预设**：自定义并分享你的修图参数模板
- **轻量无广告**：核心包体 < 15MB，专注纯粹修图体验

## 🚀 快速开始

### 环境要求
- Android Studio 2022+
- JDK 17
- Gradle 8.0+

### 安装步骤
```bash
# 克隆仓库
git clone https://github.com/ZYZ-Labs/GlowCam.git

# 导入 Android Studio
File > Open > 选择项目根目录

# 构建并运行
Build > Make Project 后连接设备调试
```

## 📖 使用指南

### 基础功能

1. **拍摄/导入照片**：点击主界面相机按钮或图库图标

2. **智能美颜**：滑动调节「磨皮」「瘦脸」「大眼」强度

3. **滤镜选择**：左右滑动预览并应用不同风格

   ```java
   // 代码示例：应用「蜜桃氧气」滤镜
   GlowFilter.applyPreset(photoView, FilterPreset.PEACH_OXYGEN);
   ```

### 高级功能

- **局部调整**：长按图片区域单独调节亮度/饱和度
- **批量导出**：支持 9 宫格拼图一键处理
- **手势快捷**：双指捏合缩放细节，三指滑动撤销操作

## 🤝 如何贡献

欢迎提交 Issue 或 Pull Request！请先阅读 贡献指南：

1. Fork 本项目并创建分支 (`git checkout -b feature/your-feature`)
2. 遵循 代码规范 提交修改
3. 确保单元测试通过 (`./gradlew test`)
4. 提交 PR 并描述变更内容

## 📜 许可证

本项目基于 **MIT 协议** 开源：

```text
MIT License

Copyright (c) 2025 ZYZ-Labs

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

## ☎️ 联系我们

- 项目维护：@SilverIceKey
- 反馈邮箱：z516798599@gmail.com
- 用户讨论区：Discussions