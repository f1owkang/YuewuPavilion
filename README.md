# 月梧阁（Quartz v4驱动）

> “[那些] 敞开大门工作的人会遭到各种打扰，但 [他们] 也偶尔会得到一些关于这个世界是什么以及什么可能很重要的线索。” 
>
> — Richard Hamming

Quartz 是一套工具，帮助你免费将你的数字花园和笔记发布为网站。

Quartz v4 版本进行了程序重构，专注于用户的可扩展性和易用性。

# 部署月梧（Github Pages）

| 名称 | 备注 | 可选 |
| :---: | :---: | :---: |
| 注册域名 | 用于自定义域名 | 可选 |
| Cloudflare | 用于加速网站访问（~~减速器~~）| 可选 |
| Github账号 | 可以进行Github Action的账号 | 必需 |

1. 克隆本项目到自己的Github账号。
2. 启用克隆项目的Github Action，配置环境Secrets。

| 名称 | 备注 | 示例 |
| :---: | :---: | :---: |
| GIT_USER_EMAIL | 用于存储 user.email | yuewuwork@outlook.com |
| GIT_USER_NAME | 用于存储 user.name | GithubAction |

3. 在克隆的项目中找到Github Pages，Source选择Github Action。
4. （可选）Custom domain中填写你的自定义域名，将注册域名托管到Cloudflare，在Cloudflare中填写如下解析。

| 类型 | 名称 | 内容 |
| :---: | :---: | :---: |
| CNAME | * | Github用户名.github.io |
| CNAME | @ | Github用户名.github.io |

部署成功，等待一段时间，你就可以访问你的项目地址了！

# 项目构建

[![Deploy Quartz site to GitHub Pages](https://github.com/kslpix/YuewuPavilion/actions/workflows/deploy.yaml/badge.svg?branch=main)](https://github.com/kslpix/QiyuePavilion/actions/workflows/deploy.yaml)

# 捐赠项目（Quartz）

<p align="center">
  <a href="https://github.com/sponsors/jackyzha0">
    <img src="https://cdn.jsdelivr.net/gh/jackyzha0/jackyzha0/sponsorkit/sponsors.svg" />
  </a>
</p>
