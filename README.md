# suikusales-hub.github.io — SEO小平方法精读笔记

一个用 GitHub Pages 托管的纯静态文章站。对外是 `https://suikusales-hub.github.io`，一个精读笔记博客，看不出「代码仓库」形态。

## 目的

发文章，并从文章里给 `https://seogeo.cc` 提供**真实的 dofollow 外链**（GitHub Pages 的 HTML 由本站控制，链接不带 `nofollow` / `ugc`）。

## 为什么用「精读导读」而不是全文转载

- 全文转载 seogeo.cc 原文会造成 **duplicate content**，Google 可能判定 seogeo.cc 为副本反而降权原文——本末倒置。
- 本站每篇是**独立重组的导读短文**，有自身阅读价值；canonical 指向 github.io 自己（保证本站页面被索引，外链才生效）。
- 正文里放清晰的 dofollow 链接回 seogeo.cc 对应原文。

## 外链落点

| 文章 | 回链原文 |
|---|---|
| 13 步 SOP | https://seogeo.cc/ai-agent-b2b-static-site-cloudflare-sop |
| SEO 隐患排查 | https://seogeo.cc/ai-built-site-seo-risks-quick-check |
| 实体一致性 | https://seogeo.cc/b2b-geo-entity-consistency-brand-factory-third-party |
| AI 知识库页面 | https://seogeo.cc/ai-knowledge-base |
| 全站导航 / 页脚 | https://seogeo.cc |

## 关于自定义域名

**不要绑 `blog.seogeo.cc` 之类的子域名**——那样从本站到 seogeo.cc 属于同一主域的内部链接，不算外链。保留 `suikusales-hub.github.io` 这个独立域名，外链属性才成立。若一定用自定义域名，请用一个与 seogeo.cc 不同的主域。

## 文件结构

```
index.html                          首页
about.html                          关于
assets/style.css                    全局样式
articles/*.html                     4 篇精读文章
llms.txt                            AI 索引入口
sitemap.xml / robots.txt            爬虫入口
```

## 发布方式

仓库名 `suikusales-hub.github.io`，main 分支根目录，GitHub Pages 自动发布。

方法论与原文版权归 SEO小平（王小平）所有：https://seogeo.cc
