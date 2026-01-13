# BaoTa Panel Plugins

宝塔面板插件修改版 (授权绕过)

## Author
- **MissChina** <391475293@qq.com>

## Plugins List (17)

| Plugin | Description |
|--------|-------------|
| bt_ssh_auth | SSH密钥认证 |
| btwaf | Nginx防火墙 |
| btwaf_httpd | Apache防火墙 |
| load_balance | 负载均衡 |
| masterslave | 主从复制 |
| monitor | 堡塔监控 |
| msg_push | 消息推送 |
| mysql_replicate | MySQL同步 |
| nfs_tools | NFS工具 |
| ossfs | 对象存储 |
| rsync | 文件同步 |
| syssafe | 系统安全 |
| tamper_core | 防篡改核心 |
| tamper_proof_refactored | 防篡改重构版 |
| task_manager | 任务管理 |
| total | 网站统计 |
| wp_toolkit | WordPress工具 |

## Download URLs (v1.0.0)

```
https://github.com/CNYuns/files/releases/download/v1.0.0/bt_ssh_auth.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/btwaf.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/btwaf_httpd.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/load_balance.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/masterslave.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/monitor.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/msg_push.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/mysql_replicate.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/nfs_tools.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/ossfs.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/rsync.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/syssafe.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/tamper_core.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/tamper_proof_refactored.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/task_manager.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/total.zip
https://github.com/CNYuns/files/releases/download/v1.0.0/wp_toolkit.zip
```

## Usage

### Install Plugin

```bash
# Download and extract to BaoTa plugin directory
wget https://github.com/CNYuns/files/releases/download/v1.0.0/btwaf.zip
unzip btwaf.zip -d /www/server/panel/plugin/
```

## Release (For Maintainer)

Push a tag to trigger auto release:

```bash
git tag v1.0.0
git push origin v1.0.0
```

Or manually trigger via GitHub Actions workflow_dispatch.
