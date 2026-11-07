# 02-git-my-docs

## 项目简介
本项目是基于 MkDocs Material 主题搭建的个人静态技术文档网站。通过 GitHub Actions 实现了文档的自动构建与部署，当推送 Markdown 源码到 `main` 分支时，会自动触发工作流更新 GitHub Pages 网站。

## 相关链接
- **最终网站地址**：https://OdeurCuivre.github.io/02-git-my-docs/
- **个人实验报告入口**：[个人实验报告](report/README.md)

## 本地预览命令
如果你在本地运行此项目，请使用以下命令：

```bash
# 创建并激活虚拟环境 (Windows)
python -m venv .venv
source .venv/Scripts/activate

# 安装依赖
python -m pip install -r requirements.txt

# 启动本地预览服务器
python -m mkdocs serve