# Mac 使用指南 - 奇淫技巧篇

## 1. 快捷键进阶技巧
- Command + Space: 快速启动 Spotlight 搜索
- Command + Shift + 5: 截图/录屏工具
- Command + Control + Q: 快速锁屏
- Command + Option + D: 显示/隐藏程序坞
- Control + Command + F: 全屏切换
- fn + delete : 向后删除字符串,与 Windows 的 delete insert 功能键相同;
- Command + , : 能打开 Mac 上几乎所有软件的设置;
- Command + w : 关闭当前程序的 tab, 例如 Chrome, Safari 的单个页面;
- Command + q : 关闭当前程序,并退出后台;
- Command + 0,1,2... : 切换当前程序的 tab, 例如 Chreme, Safari;
- Command + [ : 在有tab 页面的程序中向左切换 tab; 例如 Chreme, Safari;
- Command + ] : 在有tab 页面的程序中向右切换 tab; 例如 Chreme, Safari;
- Option + Command + esc : 当程序未响应后可以打开任务管理界面,选择未响应的应用然后退出;
- Command + tab : 和 Windows 的 alt + tab 的效果类似;
- Command + Shift + .: 显示/隐藏 Finder 的隐藏目录;

## 2. 隐藏功能
- 按住 Option 键点击菜单栏图标可查看更多选项
- 按住 Command 键拖动非激活窗口可在后台移动窗口
- 在 Finder 中按住 Space 可快速预览文件
- 按住 Shift 键调整音量/亮度可实现更精细的调节
- 在终端输入 `defaults write com.apple.finder AppleShowAllFiles YES` 显示隐藏文件

## 3. 效率神器
- 设置 Hot Corners 热区快速触发操作: [热区设置教程](https://support.apple.com/zh-cn/guide/mac-help/mchlp3000/mac) - 移动鼠标到屏幕角落触发功能
- Automator 自动化处理重复任务: [自动化工作流程](https://support.apple.com/zh-cn/guide/automator/welcome/mac) - 创建自定义工作流程
- 开启 iCloud Drive 桌面与文稿同步: [iCloud 同步设置](https://support.apple.com/zh-cn/HT204025) - 跨设备访问文件
- AirDrop 快速传输文件: [AirDrop 使用指南](https://support.apple.com/zh-cn/HT203106) - 设备间无线传输
- Spotlight 高级搜索技巧: [搜索技巧指南](https://support.apple.com/zh-cn/HT204014) - 快速定位文件和信息
- Mission Control 多桌面管理: [桌面管理教程](https://support.apple.com/zh-cn/HT204100) - 高效组织工作空间
- Quick Look 快速预览功能: [预览功能说明](https://support.apple.com/zh-cn/guide/mac-help/mh14119/mac) - 无需打开即可查看文件
- Time Machine 自动备份系统: [备份设置指南](https://support.apple.com/zh-cn/HT201250) - 保护数据安全
- 键盘快捷键自定义: [快捷键设置教程](https://support.apple.com/zh-cn/HT201236) - 打造个性化操作体验
- 手势操作进阶技巧: [触控板使用指南](https://support.apple.com/zh-cn/HT204895) - 提升操作效率
- Split View 分屏功能: [分屏模式教程](https://support.apple.com/zh-cn/HT204948) - 同时处理多任务
- 标签页管理技巧: [标签页使用指南](https://support.apple.com/zh-cn/guide/mac-help/mh35921/mac) - 高效管理多窗口
- 快速笔记和便签: [备忘录使用技巧](https://support.apple.com/zh-cn/HT205773) - 随手记录想法

## 4. 系统优化
- 定期清理系统缓存和临时文件: [系统清理指南](https://support.apple.com/zh-cn/HT206996) - 释放磁盘空间
- 使用活动监视器查看系统资源占用: [活动监视器使用教程](https://support.apple.com/zh-cn/guide/activity-monitor/welcome/mac) - 监控 CPU、内存、网络等资源
- 关闭不必要的开机启动项: [启动项管理指南](https://support.apple.com/zh-cn/HT201988) - 提升开机速度
- 使用磁盘工具修复权限和磁盘错误: [磁盘工具使用指南](https://support.apple.com/zh-cn/HT210898) - 维护系统健康
- 开启 FileVault 加密保护数据: [FileVault 使用教程](https://support.apple.com/zh-cn/HT204837) - 保护数据安全
- 管理系统存储空间: [存储空间管理指南](https://support.apple.com/zh-cn/HT206996) - 优化存储使用
- 定期运行系统维护脚本: [系统维护指南](https://support.apple.com/zh-cn/HT202516) - 自动清理系统
- 优化电池使用: [电池管理指南](https://support.apple.com/zh-cn/HT204054) - 延长电池寿命
- 配置系统性能模式: [性能设置指南](https://support.apple.com/zh-cn/HT202528) - 平衡性能与能耗
- 使用 CleanMyMac 等工具进行深度清理: [第三方清理工具使用建议](https://support.apple.com/zh-cn/HT201860) - 全面系统优化

## 5. 实用小技巧
- `⌘ + ;` 快速查找拼写错误
- `⌘ + ⇧ + .` 显示/隐藏隐藏文件
- `⌥ + 点击` 菜单栏图标查看更多选项

## 6. 终端命令技巧
- `sudo lsof -i :端口号` 查看端口占用
- `killall Finder` 重启访达
- `caffeinate` 防止系统休眠
- `say "文本"` 让 Mac 朗读文字
- `pbcopy < file` 复制文件内容到剪贴板
- `top` 或 `htop` 查看系统资源占用情况
- `df -h` 查看磁盘空间使用情况
- `du -sh *` 查看当前目录下各文件/文件夹大小
- `history` 查看命令历史记录
- `open .` 在访达中打开当前目录
- `pmset noidle` 临时阻止系统休眠
- `networksetup -setairportpower en0 on/off` 开关 WiFi
- `screencapture -c` 截图并保存到剪贴板
- `defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}'; killall Dock` 添加程序坞分隔符
- `sips -r 90 image.jpg` 旋转图片
- `mdfind` 命令行版本的 Spotlight 搜索
- `ditto` 保留文件属性复制文件/文件夹
- `softwareupdate --list` 查看可用系统更新
- `system_profiler SPHardwareDataType` 查看硬件信息
- `diskutil list` 查看磁盘分区信息

## 7. 安全与隐私
- 使用防火墙保护系统安全: [防火墙设置指南](https://support.apple.com/zh-cn/HT201642) - 配置入站连接和应用访问权限
- 定期更新系统和应用: [系统更新指南](https://support.apple.com/zh-cn/HT201541) - 及时修复安全漏洞和系统问题
- 使用强密码保护账户: [Apple ID 密码指南](https://support.apple.com/zh-cn/HT201355) - 创建和管理安全密码
- 开启双重认证: [双重认证设置](https://support.apple.com/zh-cn/HT204915) - 增加 Apple ID 账户安全性
- 谨慎安装第三方应用: [App 安全性检查](https://support.apple.com/zh-cn/HT201940) - 验证应用来源和安全性
- FileVault 加密硬盘: [FileVault 使用指南](https://support.apple.com/zh-cn/HT204837) - 保护数据安全
- 管理应用权限设置: [隐私设置指南](https://support.apple.com/zh-cn/HT210897) - 控制应用访问权限
- Safari 隐私浏览: [Safari 隐私功能](https://support.apple.com/zh-cn/guide/safari/sfri11471/mac) - 保护浏览隐私
- 设置查找我的 Mac: [查找功能设置](https://support.apple.com/zh-cn/HT204756) - 远程定位和保护设备
- 备份敏感数据: [Time Machine 使用指南](https://support.apple.com/zh-cn/HT201250) - 定期备份重要信息

## 8. 故障排除
- 重置 NVRAM/PRAM: [官方指南](https://support.apple.com/zh-cn/HT204063) - 解决启动、声音、显示等基础设置问题
- 安全模式启动系统: [官方教程](https://support.apple.com/zh-cn/HT201262) - 排除第三方软件冲突和系统问题
- 使用磁盘急救修复问题: [磁盘工具使用指南](https://support.apple.com/zh-cn/HT210898) - 修复磁盘错误和权限问题
- 重置 SMC: [系统管理控制器重置](https://support.apple.com/zh-cn/HT201295) - 解决电源、风扇、电池等硬件问题
- 系统日志查看与分析: [Console使用指南](https://support.apple.com/guide/console/welcome/mac) - 诊断系统错误和应用崩溃
- 硬盘急救模式: [Recovery Mode指南](https://support.apple.com/zh-cn/HT201314) - 系统恢复和重装
- 诊断测试: [Apple诊断](https://support.apple.com/zh-cn/HT202731) - 检查硬件问题
- Time Machine恢复: [备份恢复教程](https://support.apple.com/zh-cn/HT203981) - 从备份中恢复系统和文件

## 9. 生产力提升
- [Alfred](https://www.alfredapp.com/) 替代 Spotlight,支持工作流和快速启动
- [Better Touch Tool](https://folivora.ai/) 自定义手势和快捷键
- [Magnet](https://magnet.crowdcafe.com/) 或 [Rectangle](https://rectangleapp.com/) 进行窗口管理
- [iTerm2](https://iterm2.com/) 增强终端体验,支持分屏和主题定制
- [Homebrew](https://brew.sh/) 管理软件包和命令行工具
- [Karabiner](https://karabiner-elements.pqrs.org/) 自定义键盘映射
- [CleanShot X](https://cleanshot.com/) 优化截图体验
- [Bartender](https://www.macbartender.com/) 整理菜单栏图标
- [PopClip](https://pilotmoon.com/popclip/) 增强文本选择功能
- [Keyboard Maestro](https://www.keyboardmaestro.com/) 创建自动化工作流
- [IINA](https://iina.io/) 现代化的视频播放器
- [Vimac](https://vimacapp.com/) 现代化的鼠标手势工具
- [Raycast](https://www.raycast.com/) 替代 Spotlight 的效率工具
- [Snipaste](https://www.snipaste.com/) 截图工具,支持贴图和标注
- [PicGo](https://picgo.app/) 图床工具,支持多种图床
- [PicGo-Core](https://github.com/PicGo/PicGo-Core) 图床工具核心库
