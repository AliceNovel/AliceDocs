---
title: "Introduction"
description: "Get started with Anov Syntax"
summary: ""
date: 2024-12-18T22:11:00+09:00
lastmod: 2024-12-18T22:11:00+09:00
draft: false
slug: "1"
weight: 101
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

### How to start

Welcome to the Alice System. All Systems in the Alice Project include the Anov Syntax and the Anproj file format.

Below are the official recommendations on how to do this.

- Using Alice Novel
- Using Alice Console
- Using Aqua Notes (beta)

And then, you can also use tools created by therd-parties.

{{< tabs "create-new-site" >}}
{{< tab "Alice Novel" >}}

### Alice Novel

The Alice Novel is the greatest tool created by the Alice Project.

#### Installation

Microsoft Store version is here:

<a href="https://apps.microsoft.com/detail/9mvs80m1ps8v?referrer=appbadge&mode=direct">
	<img src="https://get.microsoft.com/images/en-us%20light.svg" width="200"/>
</a>

ZIP version is here:

1. Access to <https://github.com/AliceNovel/AliceNovel/releases/latest>
1. Scroll down and download `<os>-ci-build.zip` in the `Assets` section
1. Unarchive the ZIP file

Then, you can use the executable file.

#### How to use

You can read `.anproj` file with it. You can't read `.anov` file for now.

{{< /tab >}}
{{< tab "Alice Console" >}}

### Alice Console

The Alice Console is useful CLI tool created by the Alice Project.

#### Installation

1. Access to <https://github.com/AliceNovel/AliceConsole/releases/latest>
1. Scroll down and download `<os>-<architecture>.zip` in the `Assets` section
1. Unarchive the ZIP file

After add permission to it, you can use the command.

#### How to use

You can read `.anov` file with it.

```shell
# e.g.
./AliceConsole main.anov
```

{{< /tab >}}
{{< tab "Aqua Notes" >}}

### Aqua Notes (beta)

The Aqua Notes is useful web-based development tool created by the Alice Project.

#### Installation

Install is not necessary. If you want to install it, you can search about [PWA](https://web.dev/explore/progressive-web-apps).

#### How to use

1. Access to <https://alicenovel.github.io/AquaNotes/>
1. Open `Reader` page from left-bar
1. Write Anov Syntax in the textbox
1. Push `Submit` button when you finished write it

Then, push `ReadAll` button, system reads it.

{{< /tab >}}
{{< /tabs >}}
