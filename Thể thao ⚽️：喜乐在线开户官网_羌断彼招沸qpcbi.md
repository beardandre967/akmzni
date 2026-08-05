喜乐在线开户官网【Q-——333307——】喜乐在线开户官网【 辋芷《888yx●vip》 】
喜乐在线开户官网【Q-——333307——】喜乐在线开户官网【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整实战指南（2025版）

> 你是否想拥有一个完全免费的、可自定义的、支持 HTTPS 的个人博客？本文将手把手教你使用 GitHub Pages 和 Hexo 搭建一个高性能站点，全程无需购买服务器，小白也能轻松上手。

 为什么选择 Hexo + GitHub Pages？

在众多博客方案中，这对组合优势明显：

- 零成本：GitHub 提供 100GB 静态空间和免费 CDN
- 极速访问：纯静态页面，秒开无压力
- 高度定制：支持主题市场、插件生态丰富
- SEO 友好：生成的 HTML 结构利于搜索引擎收录

 第一步：环境准备与仓库创建

1. 安装 Node.js（建议 v18+）和 Git
2. 登录 GitHub，新建仓库，命名为 `你的用户名.github.io`
3. 建议勾选 “Add a README file” 初始化仓库

 第二步：本地初始化 Hexo

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo server   本地预览
```

此时访问 `http://localhost:4000`，你已成功运行第一个 Hexo 站点。

 第三步：部署到 GitHub Pages

安装部署插件并修改配置：

```bash
npm install hexo-deployer-git --save
```

编辑 `_config.yml`，在文件底部添加：

```yaml
deploy:
  type: git
  repo: https://github.com/用户名/用户名.github.io.git
  branch: main
```

执行 `hexo clean && hexo deploy`，等待片刻，浏览器访问你的博客地址即可看到线上版本。

 第四步：深度优化与常见问题

主题选择：推荐使用 Next、Butterfly 等热门主题，支持暗夜模式、字数统计等实用功能。

SEO 优化：安装 `hexo-generator-sitemap` 插件，并在 `_config.yml` 中开启站点地图。

疑问排查：遇到 404 或部署失败，先检查仓库名是否完全匹配，再确认 `_config.yml` 中的 URL 和 root 设置无误。

 结语

不要害怕尝试，遇到问题在评论区留言，我会第一时间协助解决。如果这篇文章帮助了你，请点击“在看”分享给更多需要的人，让我们一起在技术的世界里不断成长！

相关推荐：

https://github.com/waltermichael2379/dpdhyi/blob/main/ch%E1%BB%8Di%20g%C3%A0%20%F0%9F%90%94%20%EF%BC%9A%E5%85%AB%E6%96%B9%E5%AE%98%E7%BD%91%E7%99%BB%E5%BD%95_%E7%9C%89%E8%92%99%E7%88%B6%E5%B2%B8%E6%A2%81obhua.md

<img src="https://i.postimg.cc/YCXdtfFm/xilezaixian-00011.png" />

相关推荐：

https://github.com/waltermichael2379/dpdhyi/commit/15c8154b7a469c5b0a7eb202ca316ab58537d927

<img src="https://i.postimg.cc/7YnBWyYC/xilezaixian-00001.png" />
相关推荐：

https://github.com/morenospencer5864/qyacij/blob/main/C%E1%BB%91c%20Games%20%F0%9F%A5%8A%EF%BC%9A%E5%85%AB%E6%96%B9%E5%AE%98%E7%BD%91%E4%B8%BB%E7%AE%A1_%E8%B0%86%E5%A6%87%E8%86%8A%E4%BE%A5%E5%B8%82leedr.md

<img src="https://i.postimg.cc/yNkvxghx/xilezaixian-00012.png" />
相关推荐：

https://github.com/morenospencer5864/qyacij/commit/e7ef840fa799d77e12f9bf2af13d270775590781

<img src="https://i.postimg.cc/3JFLcHJ9/xilezaixian-00003.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
