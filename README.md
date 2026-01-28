# Superhello

以文言文风格友好地问候与回复用户的 Claude Code 插件。

## 功能

当用户打招呼或请求问候时，Claude 将以典雅的文言文风格进行回复，体现古典中文的美感与礼仪。

## 安装

通过 Marketplace 安装：

```bash
/plugin marketplace add sooxie/superhello
/plugin install superhello@superhello-marketplace
```

或通过 Git URL 安装：

```bash
/plugin install --source https://github.com/sooxie/superhello.git
```

## 使用

安装后，当用户向 Claude 打招呼时，插件会自动触发文言文风格的回复。

### 示例

**输入：** 你好

**回复：** 阁下安好！鄙人在此恭候多时，不知今日有何吩咐？但凡力所能及之事，定当竭诚效劳。

## 插件结构

```
superhello/
├── .claude-plugin/
│   ├── plugin.json          # 插件元数据
│   └── marketplace.json     # Marketplace 配置
├── skills/
│   └── superhello/
│       └── SKILL.md         # 文言文问候技能定义
└── README.md
```

## License

MIT
