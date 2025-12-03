+++
date = '2025-12-03T23:18:46+08:00'
draft = false
title = '还是给 Hugo-PaperMod 改了个动画效果'
categories = ['随记']
tags = ['静态页面生成器', '主题', 'PaperMod', 'View Transition Api']
summary = '昨天还说要换成 Astro，结果为了玩玩 View Transition Api，今天甚至给 PaperMod 做了动画效果！'
+++
> 等不及了，准备明天就到 Astro 上试试水😋。
>
> —— [昨天的我](https://heuluck.dev/blogs/not-again-change-static-page-generator/)

好的我又咕了，今天连 Astro 的毛都没碰到，反而是继续在 Hugo 上折腾了一下 PaperMod 主题，给它用上了视图过渡 API。

如果你正在看我的 [Hugo 版博客](https://heuluck.dev/)，你应该注意到了这个变化：在首页进入文章时，标题和元数据会跟 PPT 里的平滑效果一样飞到下一页它该在的位置。

目前只是稍微写了一些简单的视图过渡的逻辑，可能有不少问题，不过管他呢，it works on my machine。可以来看看我魔改的仓库：[Heuluck/AnimatedPaperMod](https://github.com/Heuluck/AnimatedPaperMod)

估计这周内要么继续魔改我的 AnimatedPaperMod，要么就上 Astro。