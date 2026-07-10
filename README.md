# 文件记忆助手发布仓库

这个仓库只用于发布「文件记忆助手」安装包和在线更新清单，不存放源码。

源码仓库可以继续保持私有；软件客户端只访问这里的公开文件。

## 在线更新入口

程序读取：

```text
https://raw.githubusercontent.com/zhaotf1102/file-memory-assistant-releases/main/latest.json
```

`latest.json` 示例：

```json
{
  "version": "0.5.3",
  "installer_url": "https://github.com/zhaotf1102/file-memory-assistant-releases/releases/download/v0.5.3/FileMemoryAssistant_Setup_v0.5.3.exe",
  "sha256": "",
  "notes": "更新说明"
}
```

## 发布原则

- Release 里放安装包 `.exe`。
- 仓库根目录放 `latest.json`。
- 不上传源码。
- 不上传用户数据。
- 不上传文件索引数据库。
