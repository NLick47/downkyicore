# 更新日志

## [1.0.3] - 2023-12-24

### Bug Fixes

- 修改图片生成质量
- 修复关注列表首次加载空白 Fixes #8
- 优化代码命名
- 修复dialog字体问题

### Features

- 添加弹幕屏蔽类型
- 添加重复下载提醒的设置

## [1.0.2] - 2023-12-21

### Bug Fixes

- 修复无法保存编码、画质、音质 Fixes #3  [ci skip]
- 修复视频设置样式问题
- 修复历史记录显示bug
- 修复下载设置磁盘剩余空间和取消浏览的bug
- 优化dialog样式和修复dialog的相关bug
- 修复基本设置和弹幕设置部分无法保存的问题 Fixes #5

## [1.0.1] - 2023-12-20

### Bug Fixes

- 修复下载全部无效的bug
- 修复下载管理tips显示错误
- 命名修复
- 修复多分片不显示
- 修复关注页面点击up不跳转
- 修复投稿页面样式问题

### Features

- 修改macOS最低支持版本为10.15
- Linux支持打开文件和文件夹

### Miscellaneous Tasks

- 添加更新日志
- 发布v1.0.1

## [1.0.0] - 2023-12-19

### Bug Fixes

- 修复拼写错误
- 修复解析中滚动闪退
- 修复视频详情页滚动导致选项丢失
- 修复提示框异步问题
- 修复下载列表删除无效
- 修复ui上的问题
- 正确获取临时文件路径
- Macos和linux正确获取相关目录。windows继续使用当前目录
- 正确处理各个系统的文件路径并兼容8.0中断性变更
- 修改发布配置
- 修复下载列表不显示和提示框异步问题
- 修复发布在macOS和linux上的一些问题
- Linux图标问题

### Features

- 首次完成测试
- Update README.md
- Bump Avalonia version
- 支持文件名设置支持拖动
- 更新wbi签名
- 保存当前页面服务，减少new的开销和接口调用次数
- 修改referer和origin为移动端，目前测试是可以减少风控。未经详细测试
- 升级AvaloniaUI版本
- 支持aria2
- Windows和macOS添加aria2支持
- Windows加入图标
- 添加统一的跨平台处理函数
- Macos打包脚本
- 添加windows获取aria2和ffmpeg脚本
- 完善构建
- 修正命名
- 一些属性
- 修改ci
- 修改ci
- 修改icon
- 添加图标

### Miscellaneous Tasks

- 去掉代理
- 修复构建
- 修复构建
- 修复构建
- 修复构建
- 修复构建
- 修复macOS构建
- Release v1.0.0

<!-- generated by git-cliff -->