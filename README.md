基于 Hexo 框架构建的静态个人博客。
博客预览: https://blog.innovpeaks.com

欢迎来到我的个人博客项目的源代码仓库。这里记录了我的技术学习笔记、生活随想和各种有趣的发现。

✨ 博客特色
极速体验: 基于 Hexo 生成的静态页面，加载速度快。

响应式设计: 适配移动端与桌面端，随处可阅。

简洁美学: 使用 Fluid主题，追求简洁与内容至上。


数据统计: 集成 Google Analytics/Umami/百度统计，


🚀 快速开始
如果你想在本地运行或基于此项目构建你自己的博客，请遵循以下步骤。

前置要求
Node.js: 请确保你的 Node.js 版本在 18.0 及以上。

Git: 用于版本管理和部署。

一个 GitHub 账户: 用于部署和托管。

安装与运行
克隆项目:

bash
git clone https://github.com/JunHL2021/junhl2021.github.io.git
cd junhl2021.github.io
安装依赖:

bash
npm install
本地启动服务器:

bash
hexo server
# 或者简写
hexo s
服务器启动后，在浏览器中打开 http://localhost:4000 即可预览博客。

📝 常用命令
以下是一些在开发过程中常用的 Hexo 命令：

bash
# 创建一篇新文章
hexo new "我的新文章"

# 生成静态文件
hexo generate
# 或
hexo g

# 部署到服务器（如 GitHub Pages）
hexo deploy
# 或
hexo d

# 组合命令：清空缓存、生成文件并部署
hexo clean && hexo g -d
🏗️ 项目结构
text
.
├── _config.yml           # Hexo 主配置文件

├── _config.[theme].yml   # 主题配置文件（如果你有）

├── source/               # 源文件目录

│   ├── _posts/          # 文章（Markdown 文件）

│   └── about/           # “关于”页面等其他页面

├── themes/               # 主题目录

│   └── [your-theme]/    # 你所使用的主题

├── public/               # 执行 `hexo generate` 后生成的静态文件（无需手动修改）

└── scaffolds/            # 模板文件夹

🌐 部署
本博客通过 GitHub Actions 自动部署到 GitHub Pages。每当你向 main/master 分支推送代码时，CI 流程会自动运行 hexo clean && hexo generate && hexo deploy。

🤝 贡献
虽然这是一个个人博客，但我非常欢迎任何形式的建议和讨论。

发现错别字或有更好的表述？ 欢迎直接提交 Issue 或 Pull Request。

有感兴趣的话题想让我写？ 可以通过 Issue 告诉我。

📄 许可证
本项目采用 MIT 许可证开源。这意味着你可以自由地使用本博客的代码，但请务必保留原作者的版权信息。

🙏 致谢
感谢 Hexo 提供优秀的静态博客框架。

感谢 主题名称 提供的精美主题。

感谢 GitHub 提供的免费托管服务。
