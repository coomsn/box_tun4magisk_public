### 2024.11.11
- 增加xray内核：`通过sing-box的webui切换使用仅xray支持的节点，如xhttp、splithttp`

### 文件路径
- 配置文件路径：`/box_tun/confs/`
- 自动备份路径：`/box_tun/`
- 自动还原路径：`/box_tun/confs/`、 `/box_tun/xray/`

### 规则相关
- 规则订阅脚本路径：`/box_tun/confs/srs`
- 本地规则存储路径：`/box_tun/confs/rules`
- 规则模板路径：`/box_tun/confs/rules/rules_template.json`

### 注意事项
- 支持热点共享、usb共享、网关代理。
- 支持黑白名单功能，需自行在 `.json` 文件中配置。
