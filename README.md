# 🔎 0.zone 综合查询工具

基于 0.zone API 的五合一企业资产信息查询平台。

**五大模块：** 信息系统 / 移动端应用 / 域名 / 邮箱 / 代码文档

---

## 快速开始

```bash
pip install -r requirements.txt
python 00query_gui.py
```

或下载打包好的 `00query.exe`（无需 Python，双击运行）。

> 首次使用需注册 [0.zone](https://0.zone) 获取 API Key，在程序右上角配置。

---

## 功能一览

- 多模块查询：网站、App、域名、邮箱、泄露代码
- 高级搜索语法：`==` 包含、`=` 精确、`&&` 与、`||` 或、`()` 分组
- 疑似信息系统智能分析（企业黄页）
- 结果导出 Excel / CSV
- 17 种界面主题一键切换
- 内嵌完整语法指南

---

## 项目文件

| 文件 | 说明 |
|------|------|
| `00query_gui.py` | 主程序 |
| `00query_config.json` | 本地配置文件（已加入 `.gitignore`） |
| `requirements.txt` | Python 依赖 |
| `语法指南.txt` | 查询语法文本参考 |

---

## 注意事项

- **API Key 已列入 `.gitignore`，不会提交到仓库**
- API 有每日免费查询次数限制
- 打包 exe 可能被杀毒软件误报，属正常现象，源码可审计

---

## 作者

**地图大师** — B站：[space.bilibili.com/41150425](https://space.bilibili.com/41150425) · 微信公众号：地图大师的漏洞追踪指南

## 致谢

- [0.zone](https://0.zone) 提供数据 API
- [ttkbootstrap](https://github.com/israel-dryer/ttkbootstrap) 主题库
