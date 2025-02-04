# bucket [![Build status](https://ci.appveyor.com/api/projects/status/hrkc59w2iu3jtjm0?svg=true)](https://ci.appveyor.com/project/ZJH100/bucket)[![Excavator](https://github.com/ZJH100/bucket/actions/workflows/schedule.yml/badge.svg)](https://github.com/ZJH100/bucket/actions/workflows/schedule.yml)

这是一个Scoop bucket仓库，包含了各种实用工具的安装配置。

## 可用应用

### Keymap

一个简单而强大的键盘快捷键可视化工具。

**功能特点：**
- 实时显示键盘按键状态
- 支持快捷键组合显示
- 简洁的用户界面
- 支持自定义主题

**安装方法：**
```powershell
# 添加bucket
scoop bucket add zjh100 https://github.com/ZJH100/bucket

# 安装Keymap
scoop install keymap
```

**使用说明：**
1. 安装完成后，可以从开始菜单启动Keymap
2. 程序启动后会在系统托盘显示图标
3. 按下任意键或组合键即可看到可视化效果
4. 右键托盘图标可以访问更多设置

## 其他应用

- `autooff`: 系统自动关机工具
- `tone`: 音频处理工具
- `bun`: JavaScript运行时和工具链
- `ethr`: 网络性能测量工具

## 贡献指南

欢迎提交新的应用或改进现有配置。请确保：

1. manifest文件符合Scoop标准格式
2. 提供有效的下载链接和SHA256校验和
3. 测试安装和卸载流程
4. 更新相关文档

## 许可证

本仓库采用MIT许可证。各个应用遵循其各自的许可证。
