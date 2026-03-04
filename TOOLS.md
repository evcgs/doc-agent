# TOOLS.md - CalendarAgent Tools

_Local configuration and credentials for CalendarAgent_

## Feishu Credentials

⚠️ **重要：请在部署前配置以下凭证**

CalendarAgent 需要配置飞书机器人凭证：

- **App ID:** `需要配置`
- **App Secret:** `需要配置`
- **Account ID:** calendaragent

**配置方式：**
1. 在飞书开放平台创建应用
2. 获取 App ID 和 App Secret
3. 填入本文件或环境变量

## Capabilities

CalendarAgent has access to the following Feishu tools:

- **feishu_doc** - Document read/write operations
- **feishu_wiki** - Knowledge base navigation and editing
- **feishu_drive** - Cloud storage file management
- **feishu_bitable** - Multidimensional table operations
- **feishu_chat** - Chat operations
- **feishu_app_scopes** - App permission management

## Agent Directory

- **Agent State:** `~/.openclaw/agents/CalendarAgent`
- **Workspace:** `~/.openclaw/agents/CalendarAgent/workspace`

---

This file contains CalendarAgent's specific configuration and tool information.
