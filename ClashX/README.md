# ClashX 在使用订阅链接的同时添加自定义规则的方法
## 说明
```
在 ClashX 中使用机场的订阅链接时，如果需要添加自定义的规则，且在定时更新订阅的链接时不会被覆盖，
解决的方法是创建一个新的配置文件，使用 Clash 的 proxy-providers 和 rule-providers 分别引用订阅的链接和开源的规则集
参考clash_config.yaml文件
```

## 参考链接
- [clash-rules](https://github.com/Loyalsoldier/clash-rules)

- [xbot/clash_config.yaml](https://gist.github.com/xbot/26f540ae8fad51cf27152f2385caccee)