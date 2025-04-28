---
layout: archive
permalink: /blogs/
title: "Blogs"
---
<style>
/* 精准字体控制方案 */
.page__content {
  /* 中文独立字体栈 */
  --zh-font: "SimSun", "Songti SC", "Noto Serif CJK SC", serif;
  
  /* 英文系统字体栈 */
  --en-font: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, 
            "Helvetica Neue", Arial, sans-serif;

  /* 混合字体策略 */
  font-family: var(--zh-font), var(--en-font);
}

/* 强制英文元素使用原生字体 */
.page__content {
  /* 数字和拉丁字符 */
  [lang=en], [class*="en"],
  :matches(code, pre, var, kbd, samp),
  :not(:lang(zh)):not(:lang(cn)) {
    font-family: var(--en-font) !important;
  }
}

/* 代码块保持等宽 */
pre, code {
  font-family: Monaco, Consolas, "Lucida Console", monospace !important;
}
</style>

## 笔记

### 2025年4月

- **4月24日星期四**<br>这是中文内容 English text 123<br>

- **4月25日星期五**<br>Another English entry 中文混合<br>


## 笔记

### 2025年4月

- **4月24日星期四**<br>这里是输入的内容。<br><!--注释掉了的部分-->

- **4月25日星期五**<br>这里是下一条

---

### 单独标题

这样是不是独立的？

---

>高亮的内容
>单独强调
