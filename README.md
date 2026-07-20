# config

Shadowrocket 配置文件。

| 文件 | 用途 |
|---|---|
| `miaogic.conf` | **主文件**,以后改这个 |
| `config.conf` | 旧文件名的兼容副本,内容与主文件一致 |

分发地址(文档里用的就是这个):

```
https://cdn.jsdmirror.com/gh/echoowall/config@main/miaogic.conf
```

两个文件的首行都是 `#!MANAGED-CONFIG`,且**都指向 miaogic.conf**,
所以用旧链接的客户下次自动更新时会迁移到新地址。

> ⚠️ 改配置时**两个文件都要改**(除首行外内容需保持一致)。
> ⚠️ CDN 有缓存,改完想立即生效需刷新:
> `curl https://purge.jsdelivr.net/gh/echoowall/config@main/miaogic.conf`
> 确认旧链接没人用后(看 GitHub Insights → Traffic),可以删掉 `config.conf`。
