# 云宝也能读得懂的AI

基于 Hexo + Butterfly 的 AI 入门连载网站。

## 本地开发

需要先安装 Node.js LTS。

```bash
npm install
npm run server
```

默认访问：

```text
http://localhost:4000
```

## 写文章

文章放在：

```text
source/_posts/
```

第一章：

```text
source/_posts/01-ai-is-not-a-robot.md
```

新增文章时，复制第一章顶部的 front matter，然后修改标题、日期、分类和标签。

## 构建

```bash
npm run build
```

构建产物会生成到：

```text
public/
```

## 部署

推荐 Netlify 或 Cloudflare Pages。

Netlify:

```text
Build command: npm run build
Publish directory: public
```

Cloudflare Pages:

```text
Build command: npm run build
Build output directory: public
Node version: 20 或 22
```

部署成功后，把生成的网址发给对方即可。
