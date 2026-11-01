# CHANGELOG

## v1.0.8

- 修复初次使用插件或无历史数据时，因数据目录未创建导致读写 `bot_data.json` 抛出 `FileNotFoundError` 的问题。
- 在 `BotMonitorDB` 构造时自动同步创建父级目录并做空数据初始化。

## v1.0.7

- 新增人机消息屏蔽功能，配置项 `enable_message_block` 默认为开启状态。

## v1.0.6

- 改用官方推荐的 get_astrbot_plugin_data_path 获取数据目录

## v1.0.5

- 在扫描群成员时，将当前机器人账号从已检测到的人类机器人列表中排除。
