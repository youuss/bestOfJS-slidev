---
# try also 'default' to start simple
theme: bricks
# page transition
transition: slide-left
# use UnoCSS
css: unocss
---

# Best of Js
最好的 JavaScript、HTML 与 CSS 库

---
layout: default
---
<Vue w="20" h="20" />

# [Vue](https://cn.vuejs.org)

* Vue 2.x
  * Vue 2.7 会以其发布日期，即 2022 年 7 月 1 日开始计算，提供 18 个月的长期技术支持 (LTS：long-term support)。
  * Vue 2 将在 2023 年 12 月 31 日之后终止支持。
* Vue 3.x
  * 全面拥抱 TypeScript
  * [composition API](https://cn.vuejs.org/guide/extras/composition-api-faq.html)是Vue3的核心，它是一种基于函数的API，可以让我们更好地组织代码，更好地复用逻辑，更好地进行测试。
  * 主流技术栈：Vue3 + Vite + Vue Router + Pinia + TypeScript



---
layout: PageOne
---
<Vite w="20" h="20" />

# [Vite](https://vitejs.dev/)

* Vite 是一个基于浏览器原生 ES 模块的开发服务器，它可以显著提升前端开发体验；
* Vite 4.0发布，在2023年有望替代webpack；


---
layout: default
---
<Nuxt w="20" h="20" />

# [Nuxt](https://nuxt.com/)

* Nuxt.js 是一个基于 Vue.js 的框架，用于构建快速、可靠和灵活的应用程序。它特别适合用于服务端渲染 (SSR) 的应用程序，但也可以用于静态生成 (static-generated) 和单页应用 (SPA)。
* nuxt3.0发布

---
layout: PageTwo
---
<Slidev w="20" h="20" />

# [slidev](https://sli.dev/)

* 作为程序员的你，为什么不能敲敲代码，写写Markdown，然后就能做出一个漂亮的幻灯片呢？

---
layout: PageOne
---
<Deno w="20" h="20" />

# [Deno](https://deno.land/)

* Deno 是一个 JavaScript 和 TypeScript 的运行时，由 Ryan Dahl 开发。它的目标是提供一个替代 Node.js 的更简单和更安全的 JavaScript 运行时。
* Deno 与 Node.js 不同的是，它不使用 npm 包管理器，而是内置了一个模块系统，可以直接从 URL 加载代码。这样可以减少在项目中引入依赖的复杂性，同时还能使您的代码更具可移植性。
* Deno 还内置了一些常用的工具，例如格式化、检查和测试，使得您可以直接从命令行启动您的代码。
* 总体而言，Deno 提供了一个简单、现代的 JavaScript 开发环境，可以作为替代 Node.js 的一种选择。

---
layout: PageThree
---
<Bun w="20" h="20" />

# [Bun](https://bun.sh/)

* Bun 是一个现代的 JavaScript 运行时，就像 Node 或 Deno。它是从头开始构建的，专注于三个主要方面：
  * 快速启动（它考虑了边缘情况）。
  * 新的性能水平（扩展 JavaScriptCore，引擎）。
  * 成为一个伟大而完整的工具（打包程序，转译器，包管理器）。
* Bun 是一个 JavaScript 运行时，但是它的目标是成为一个更好的 Node.js。
* 不同于 Node.js 和 Deno 使用的是 V8 引擎，Bun 使用了 JavaScriptCore 引擎，不同的引擎会产生不同性能；
* 使用了新兴的系统编程语言 Zig，Bun 的创建者说 Zig 缺少隐藏的控制流使得编写快速软件变得更加简单。


---
layout: PageFour
---
<Tauri w="20" h="20" />

# [Tauri](https://tauri.app/)

* Tauri 是一个开源工具包，旨在帮助开发人员使用几乎任何前端框架在桌面平台上开发应用程序。它的核心是用 Rust 编写的，并使用 Node.js 的 CLI，因此它是一种真正的多语言方法，可以方便地创建和维护高质量的应用程序。
* Tauri 的目标是提供一个简单易用的框架，可以帮助开发人员在桌面平台上开发快速、轻量级和安全的应用程序。

---
layout: PageThree
---
<Astro w="20" h="20" />

# [Astro](https://astro.build/)

* Astro是一个现代的Web框架，专为构建快速、以内容为中心的网站和应用程序而设计。
  * 它提供了一系列功能和工具，帮助开发人员快速创建和部署高性能的Web项目。
  * Astro着重于简单、速度和性能，因此是广泛的Web开发项目的理想选择，从小型博客和作品集到大型内容驱动网站和电子商务平台。
* 写静态个人博客会是一个很好的选择；

---
layout: PageTwo
---
<Turbopack w="20" h="20" />

# [TurboPack](https://turbo.build/)

* TurboPack 是一个针对JavaScript和TypeScript优化的增量打包工具，由webpack和Next.js的创造者在Vercel公司用Rust编写。
* TurboPack 拥有与webpack类似的配置方式，使用者可以方便地使用它并且不需要学习复杂的语法。同时，它还具有内置的模块缓存和预编译功能，可以提高构建速度和性能。
* TurboPack 还可以与其他构建工具，如Babel和PostCSS，无缝集成。这样，开发人员可以更轻松地使用最新的JavaScript和CSS技术，并将其转换为浏览器可以理解的代码。

---
layout: default
---
<Mastodon w="20" h="20" />

# [Mastodon](https://joinmastodon.org/)
* Mastodon是一个开源的分布式社交网络，类似于Twitter。它的目的是提供一个去中心化的社交网络，用户可以在社区内免费发布内容，互相关注，并参与讨论。
* Mastodon的特点：
  * 去中心化：Mastodon是一个分布式的网络，所有的数据都储存在用户的设备上，没有单一的中心服务器。
  * 开源：Mastodon是一个开源项目，所有人都可以免费使用它，并对其进行改进。
  * 社区驱动：Mastodon是一个社区驱动的网络，用户可以加入不同的社区，并与其他人互相关注，共同参与讨论。
  * 内容控制：Mastodon允许社区管理员设置内容管理规则，以确保社区内的内容健康、正确。
  * 高安全性：Mastodon使用加密技术保护用户的隐私，防止数据泄露和窃取。

---
layout: PageThree
---
<Arc w="20" h="20" />

# [Arc](https://arc.net/)
* Arc Browser具有以下特点：
  * 简单易用：Arc Browser具有简洁的用户界面，操作简单方便，方便用户使用。
  * 快速浏览：Arc Browser使用最先进的技术，如多核心浏览引擎和数据压缩技术，以保证用户浏览网页的速度快而流畅。
  * 安全保护：Arc Browser具有强大的安全性能，可以防止病毒、恶意软件和网络威胁，以保护用户的数据安全。
  * 多功能：Arc Browser提供多种功能，如书签管理、历史记录管理、网页截图、私密浏览模式等，以满足用户的不同需求。
  * 跨平台同步：Arc Browser支持跨平台同步，用户可以在不同的设备上使用同一个帐户，保存和同步书签、历史记录和密码等数据。

---
layout: PageOne
---
<ChatGPT w="20" h="20" />

# [ChatGPT](https://chatgpt.com/)

* GPT-3（Generative Pretrained Transformer 3）是 OpenAI 开发的一种自然语言处理模型，是目前最先进的预训练语言模型之一。它通过在大量的文本数据上进行预训练，然后使用这些预训练的知识在特定任务上进行微调，以实现高质量的文本生成和理解能力。
* ChatGPT 是基于 GPT-3 模型的一个聊天机器人，由 OpenAI 训练。它可以通过与用户的对话来回答问题、提供信息和提供建议。它的语言能力非常强，可以理解并生成与人类相似的语言，因此，它可以作为虚拟助手、客服代表和其他应用程序中的聊天接口使用。
  
  全文都是ChatGPT和我聊天的记录，同时按照自己的认知进行判断调整，我是在[这里](https://chatgpt.com/)和ChatGPT聊天的，你也可以试试 ！！。


