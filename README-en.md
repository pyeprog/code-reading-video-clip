# code-reading-video-clip

[中文版本](./README.md)

## TL;DR

In 2025, when AI tools are prevalent, why do programmers still spend 50% of their working time reading code? This video will restructure your code reading skills and teach you systematic methods to quickly read any project.

- 🔗[youtube](https://youtu.be/wdqL7n8grm0)
- 🔗[bilibili](https://www.bilibili.com/video/BV15Ko9YZEQQ/?vd_source=28f0d0a6008a195ecde014a421def1d5)

### 👉 Target Audience

- Novice Programmers: Building systematic code reading mindset
- Senior Developers: Optimizing code reading methods

### 🧑‍💻 Core Content

#### Counter-intuitive Code Reading Process (5-step Method)

- Environment Setup: Set up open-source projects in 10 minutes (Bat case study)
- Dynamic Verification: Running + Debugging = Code behavior visualization, the foundation of code reading
- Goal Focus: Use codetour to lock reading objectives
- Documentation First: AI-assisted project background extraction (Cursor tool demonstration)
- Code Understanding: From code call relationship diagrams to conceptual insights

#### Brain Science Code Reading Techniques

- Focus Function Location Method (8 scenarios)
- Breadth-first Traversal: Practice of Occam's Razor principle
- Memory Optimization Strategies:
✅ Long-term Memory: Anki+AI generated knowledge cards, supplementing knowledge reserve
✅ Short-term Memory: CodeTour note system, preventing forgetting
✅ Working Memory: Syntax replacement, reverse refactoring, selective reading, reducing cognitive load

### 📝 Video Script

The video is quite long, the script is in [video-script-en.md](./video-script-en.md), you can use LLM to do summary.
prompt can be:

"""

Summarize the outline of this article, ensuring no knowledge points are missed but keeping the expression concise.
Then pick out the most worthwhile content to introduce.
Finally, if I am a `junior/senior` developer, what advice can you give me about code reading.

"""

## 📚 Reference Materials

### 📖 Reference Books

- Code Reading: Author Diomidis Spinellis, Douban rating 7.0, recommended for beginners
- The Programmer's Super Brain: Author Felienne Hermans, Douban rating 7.5, verbose writing, not recommended for detailed reading, less technical content.

### 🎤 Reference Talks

- [Reading Other People's Code](https://youtu.be/mrXHf71lYrs?si=mdBUFALWmdtiIJDl)
- [How to Read Unfamiliar Code](https://youtu.be/wN4ZuGruiNw?si=bqzAi9Nq37XayZjT)

### 💬 Discussions

- [Any Tips on Reading Code](https://www.reddit.com/r/C_Programming/comments/15rxa0u/any_tips_on_reading_code/)
- [How to Learn Hacking](http://www.catb.org/esr/faqs/hacking-howto.html)
- [Visual Studio Enterprise Edition's Dependency Graph Feature](https://learn.microsoft.com/zh-cn/visualstudio/modeling/map-dependencies-across-your-solutions?view=vs-2022#view-dependencies)

## 📺 AtomicViz Official Tutorial

AtomicViz is a powerful code structure diagram generator that can generate code call relationship diagrams, module relationship diagrams, class relationship diagrams, method relationship diagrams, etc.

- [Short Version](https://youtu.be/ZsFmE1eRgh4?si=6jz0DIoUZapSKlK9)
- [Full Version](https://youtu.be/ZsDd4Q4E81I?si=yuZJDn--U2HD-OYR)

If you have questions, you can ask them in [AtomicViz's github issue](https://github.com/briandiloreto/AtomicViz/issues).

## 🔌 Vscode Plugins

- [AtomicViz](https://marketplace.visualstudio.com/items?itemName=AtomicConcepts.atomicviz): New plugin in 2025, used to find module or class entry methods, method dependencies, etc. Free to use. Highly recommended!
- [Codetour](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.codetour): Can be used as a note-taking tool or for recording code tutorial notes, notes can follow git branch or commit. Free to use. Recommended!
- [Navigation History](https://marketplace.visualstudio.com/items?itemName=WaylongLeon.navigation-history): Records navigation history and organizes accessed symbols into a tree based on code's call structure, also counts symbol access frequency to identify code browsing hotspots, which are usually key points or difficult points. Free to use. Recommended!

## 🤝 If This Helps You

If [Navigation History](https://github.com/pyeprog/navigation-history) has helped you, could you give it a star? 🥰
If you happen to be logged into vscode marketplace, could you leave a rating or review? 🫶
