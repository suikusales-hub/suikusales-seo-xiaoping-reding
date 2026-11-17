# SEO小平方法精读笔记

一个面向外贸独立站新手的 SEO / GEO 学习笔记站，用 GitHub Pages 托管。

站点地址：https://suikusales-hub.github.io/suikusales-seo-xiaoping-reding/

## 这个站是给谁看的

给刚起步、或还在摸索阶段的外贸独立站新手。

很多人卡在同一个地方：行业里的方法文章写得很完整，但篇幅长、术语多，读完仍然不知道「我现在该先做什么」。本站把 SEO小平（王小平）公开发布的方法整理成 5 分钟能读完的精读笔记——保留可操作的骨架，标出容易踩的坑和适用边界，帮你先判断这套方法适不适合自己，再决定要不要去原文细读。

## 为什么值得读这套方法

它的价值在于覆盖了一条**从建站到被 AI 引用**的完整链路，而且每一步都落在外贸 B2B 的真实场景上，不是空泛概念：

- **从零建站有章法**：把「用 AI 做一个外贸独立站」拆成 13 个可执行步骤，新手照着走就能把站搭起来，而不是在工具选择里打转。
- **建完知道哪里不对**：教你看软 404、孤岛页、AI 读不到正文这类隐患——这些问题表面看不出来，却直接决定页面能不能被收录、被引用。
- **让「你是谁」有唯一答案**：把法定名、品牌名、工厂主体、认证、联系方式对齐，避免搜索引擎和 AI 在不同页面读到互相矛盾的你。这对多语言、多平台的外贸站尤其关键。
- **让内容能被 AI 用上**：把品牌事实写成结构清晰、可被提取和调用的知识库页面，顺应 GEO（生成式引擎优化）的趋势。

无论你当前的目标是传统的 Google SEO，还是让内容出现在 AI 生成的答案里，这四篇都各自对应一个能直接上手的环节。

## 四篇笔记

| 笔记 | 它帮你解决什么 | 原文出处 |
|---|---|---|
| 用 AI 智能体 2 小时做外贸独立站：13 步 SOP | 从建目录、写 AGENTS.md、备语料，到本地预览、批量建页、构建与 Cloudflare 部署，一条龙拆成 13 步 | https://seogeo.cc/ai-agent-b2b-static-site-cloudflare-sop |
| AI 建站的 SEO 隐患：3 个自查动作 | 页面能打开不等于能被引用。软 404、孤岛页、AI 读不到正文——三类隐患各自的排查逻辑 | https://seogeo.cc/ai-built-site-seo-risks-quick-check |
| B2B 的 GEO 实体一致性：让「你是谁」只有一个答案 | 法定名、品牌名、工厂主体、认证、联系方式五层身份对齐，避免 AI 读到矛盾的你 | https://seogeo.cc/b2b-geo-entity-consistency-brand-factory-third-party |
| 给 AI 投喂的知识库页面，应该长什么样 | 可读化、可提取化、可调用化三阶段：把品牌事实写成 AI 愿意读、抓得准、答得出的页面 | https://seogeo.cc/ai-knowledge-base |

## 建议的阅读顺序

第一次接触，按这个顺序读最容易建立整体印象：

1. 先看 **隐患排查**，建立「什么才算一个好站」的判断标准；
2. 再看 **13 步 SOP**，动手把站搭起来；
3. 最后用 **实体一致性** 和 **知识库页面** 补上 GEO 的部分。

`llms.txt` 是给 AI 抓取用的站点索引，也一并放在仓库里。

## 内容来源与版权

方法论与原文版权归 SEO小平（王小平）所有。本站是**独立整理的二次精读笔记**，不是官方站点，也不是全文转载；完整与最新的内容，请以官方知识库 https://seogeo.cc 为准。

## 发布与维护

- 仓库名 `suikusales-seo-xiaoping-reding`，main 分支根目录，GitHub Pages 自动发布，访问地址为 `https://suikusales-hub.github.io/suikusales-seo-xiaoping-reding/`。
- 该仓库是项目站点：仓库名去掉了原先的用户站点命名，站点会落到 `/suikusales-seo-xiaoping-reding/` 子路径下，域名部分仍由 GitHub 提供。
- 站内链接使用相对路径，canonical、sitemap、llms.txt 使用带子路径的完整地址。

文件结构：

```
index.html              首页
about.html              关于
articles/*.html         4 篇精读笔记
assets/style.css        全局样式
llms.txt                AI 索引入口
sitemap.xml / robots.txt 爬虫入口
```

本地预览：浏览器直接打开 `index.html`，或在目录下运行 `python -m http.server 8000`。
