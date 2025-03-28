# code-reading-video-clip

## TL;DR

在AI工具盛行的2025年，为何程序员仍旧要花50%的工作时间来读代码？本视频将对你代码阅读技巧进行结构化重构，教你用系统化方法快速读任何项目.

- 🔗[bilibili](https://www.bilibili.com/video/BV15Ko9YZEQQ/?vd_source=28f0d0a6008a195ecde014a421def1d5)

### 👉 适合人群

- 新手程序员: 建立系统化读代码的思维
- 资深开发者: 参考优化代码阅读方法

### 🧑‍💻 核心内容

#### 反直觉读码流程(5步法)

- 环境准备：10 分钟搞定开源项目（Bat 案例实操）
- 动态验证：跑起来 + 调试 = 代码行为可视化, 此乃读代码的基础
- 目标聚焦：用 codetour 锁定阅读诉求
- 文档优先：AI 辅助提炼项目背景（Cursor 工具演示）
- 代码理解: 从代码调用关系图到概念体悟

#### 大脑科学读码术

- 焦点函数定位法(8种场景)
- 广度优先遍历：奥卡姆剃刀原则实践
- 记忆优化策略：
✅ 长期记忆：Anki+AI 生成知识卡片, 补充知识储备
✅ 短期记忆：CodeTour 笔记系统, 防止遗忘
✅ 工作记忆：语法替换, 反向重构, 选择阅读, 减少认知负担

### 📝 视频脚本

视频比较长, 视频脚本在[video-script-cn.md](./video-script-cn.md), 你可以用LLM去做summary.
prompt可以是:

"""

总结这篇文章的大纲, 要求不要遗漏任何知识点, 但表达要相对简洁.  
接着把比较值得读的内容挑出来, 进行介绍.  
最后如果我是一个`junior/senior`开发者, 在代码阅读上能给我什么建议.

"""

## 📚 参考材料

### 📖 参考书目

- 代码阅读: 作者Diomidis Spinellis, 豆瓣评分7.0, 推荐新手阅读
- 程序员超强大脑: 作者Felienne Hermans, 豆瓣评分7.5, 行文啰嗦, 不建议细读, 技术相关内容较少.

### 🎤 参考talk

- [Reading Other People‘s Code](https://youtu.be/mrXHf71lYrs?si=mdBUFALWmdtiIJDl)
- [How to Read Unfamiliar Code](https://youtu.be/wN4ZuGruiNw?si=bqzAi9Nq37XayZjT)

### 💬 一些讨论

- [Any Tips on Reading Code](https://www.reddit.com/r/C_Programming/comments/15rxa0u/any_tips_on_reading_code/)
- [How to Learn Hacking](http://www.catb.org/esr/faqs/hacking-howto.html)
- [visual studio企业版的依赖图功能](https://learn.microsoft.com/zh-cn/visualstudio/modeling/map-dependencies-across-your-solutions?view=vs-2022#view-dependencies)

## 📺 AtomicViz官方教程

AtomicViz是一款强大的代码结构图生成器, 可以生成代码的调用关系图, 模块关系图, 类关系图, 方法关系图等等.

- [简短版](https://youtu.be/ZsFmE1eRgh4?si=6jz0DIoUZapSKlK9)
- [完整版](https://youtu.be/ZsDd4Q4E81I?si=yuZJDn--U2HD-OYR)

有问题可以去[AtomicViz的github issue](https://github.com/briandiloreto/AtomicViz/issues)提问.

## 🔌 Vscode插件

- AtomicViz: 2025年新出的插件, 用来找到模块或者类的入口方法, 方法之间的依赖关系等等. 能够免费使用.
- Codetour: 可以作为笔记工具, 或者录制代码教程笔记, 笔记可以跟随git branch或者commit. 能够免费使用.
- Navigation History: 记录跳转历史, 并把访问的symbol以代码本身的调用结构去组织成树, 另外会统计symbol被访问的次数, 以此来统计代码浏览的热区symbol, 它们通常是重点或者难点. 免费使用.

## 🤝 如果对你有帮助

如果[Navigation History](https://github.com/pyeprog/navigation-history)有帮到你, 可以帮我点个star吗? 🥰
如果你碰巧还登陆了vscode marketplace, 可以留下你的评分或review吗? 🫶
