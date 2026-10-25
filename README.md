# wechat-vault-site

微信本地数字资产库 · 分析站(由 GitHub Pages 自动部署)。

- **公开区**:群聊话题梳理与分类索引
- **🔒 私聊区**:`private/index.html`,内容以 AES-256-GCM 加密存储于 `private/bundle.json`,输入密码在浏览器本地解密,明文与密码永不进仓库
- raw 层(原始聊天导出)只存在于本机,永不进入本仓库

本地重建:`python3 scripts/build_site.py`(见 yichen-wechat-local-vault 仓库)
