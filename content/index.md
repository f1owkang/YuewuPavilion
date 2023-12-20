---
title: 欢迎来到 Quartz 4
---

Quartz是一个快速、内置电池的静态站点生成器，将Markdown内容转换为完全功能的网站。成千上万的学生、开发者和教师已经在使用Quartz，发布个人笔记、网站和[数字花园](https://jzhao.xyz/posts/networked-thought)到网络上。

## 🪴 入门

Quartz要求**至少安装 [Node](https://nodejs.org/) v18.14** 和 `npm` v9.3.1 以正确运行。在继续之前，请确保在您的计算机上安装了这些。

然后，在您选择的终端中，逐行输入以下命令：

```shell
git clone https://github.com/jackyzha0/quartz.git
cd quartz
npm i
npx quartz create
```

这将引导您初始化Quartz并添加内容。完成后，查看如何：

1. [[authoring content|Writing content]] in Quartz
2. [[configuration|Configure]] Quartz's behaviour
3. Change Quartz's [[layout]]
4. [[build|Build and preview]] Quartz
5. [[hosting|Host]] Quartz online

> [!info]
> Coming from Quartz 3? See the [[migrating from Quartz 3|migration guide]] for the differences between Quartz 3 and Quartz 4 and how to migrate.

## 🔧 Features

- [[Obsidian compatibility]], [[full-text search]], [[graph view]], note transclusion, [[wikilinks]], [[backlinks]], [[Latex]], [[syntax highlighting]], [[popover previews]], [[Docker Support]], and [many more](./features) right out of the box
- Hot-reload for both configuration and content
- Simple JSX layouts and [[creating components|page components]]
- [[SPA Routing|Ridiculously fast page loads]] and tiny bundle sizes
- Fully-customizable parsing, filtering, and page generation through [[making plugins|plugins]]

For a comprehensive list of features, visit the [features page](/features). You can read more about the _why_ behind these features on the [[philosophy]] page and a technical overview on the [[architecture]] page.

### 🚧 Troubleshooting + Updating

Having trouble with Quartz? Try searching for your issue using the search feature. If you haven't already, [[upgrading|upgrade]] to the newest version of Quartz to see if this fixes your issue.

If you're still having trouble, feel free to [submit an issue](https://github.com/jackyzha0/quartz/issues) if you feel you found a bug or ask for help in our [Discord Community](https://discord.gg/cRFFHYye7t).
