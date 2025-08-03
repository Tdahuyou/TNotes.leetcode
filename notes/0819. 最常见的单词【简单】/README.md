# [0819. 最常见的单词【简单】](https://github.com/Tdahuyou/TNotes.leetcode/tree/main/notes/0819.%20%E6%9C%80%E5%B8%B8%E8%A7%81%E7%9A%84%E5%8D%95%E8%AF%8D%E3%80%90%E7%AE%80%E5%8D%95%E3%80%91)

<!-- region:toc -->

- [1. 📝 Description](#1--description)
- [2. 🎯 Solutions.1 - 暴力解法](#2--solutions1---暴力解法)

<!-- endregion:toc -->

## 1. 📝 Description

::: details [leetcode](https://leetcode.cn/problems/most-common-word/)

给你一个字符串 `paragraph` 和一个表示禁用词的字符串数组 `banned` ，返回出现频率最高的非禁用词。题目数据 **保证** 至少存在一个非禁用词，且答案 **唯一** 。

`paragraph` 中的单词 **不区分大小写** ，答案应以 **小写** 形式返回。

**注意**  单词不包含标点符号。

---

- **示例 1：**

```txt
输入：paragraph = "Bob hit a ball, the hit BALL flew far after it was hit.", banned = ["hit"]
输出："ball"
解释：
"hit" 出现了 3 次，但它是禁用词。
"ball" 出现了两次（没有其他单词出现这么多次），因此它是段落中出现频率最高的非禁用词。
请注意，段落中的单词不区分大小写，
标点符号会被忽略（即使它们紧挨着单词，如 "ball,"），
并且尽管 "hit" 出现的次数更多，但它不能作为答案，因为它是禁用词。

```

- **示例 2：**

```txt
输入：paragraph = "a.", banned = []
输出："a"
```

---

**提示：**

- `1 <= paragraph.length <= 1000`
- `paragraph` 由英文字母、空格 `' '`、和以下符号组成：`"!?',;."`
- `0 <= banned.length <= 100`
- `1 <= banned[i].length <= 10`
- `banned[i]` 仅由小写英文字母组成

:::

## 2. 🎯 Solutions.1 - 暴力解法

::: code-group

<<< ./solutions/1/1.js [js]

:::
