# [0177. 第N高的薪水【中等】](https://github.com/Tdahuyou/TNotes.leetcode/tree/main/notes/0177.%20%E7%AC%ACN%E9%AB%98%E7%9A%84%E8%96%AA%E6%B0%B4%E3%80%90%E4%B8%AD%E7%AD%89%E3%80%91)

<!-- region:toc -->

- [1. 📝 Description](#1--description)
- [2. 💻 题解](#2--题解)

<!-- endregion:toc -->

## 1. 📝 Description

::: details [leetcode](https://leetcode.cn/problems/nth-highest-salary)

表: `Employee`

```
+-------------+------+
| Column Name | Type |
+-------------+------+
| id          | int  |
| salary      | int  |
+-------------+------+
id 是该表的主键（列中的值互不相同）。
该表的每一行都包含有关员工工资的信息。
```

编写一个解决方案查询  `Employee` 表中第 `n` 高的  **不同** 工资。如果少于  `n` 个不同工资，查询结果应该为  `null` 。

查询结果格式如下所示。

---

- **示例 1:**

```
输入:
Employee table:
+----+--------+
| id | salary |
+----+--------+
| 1  | 100    |
| 2  | 200    |
| 3  | 300    |
+----+--------+
n = 2
输出:
+------------------------+
| getNthHighestSalary(2) |
+------------------------+
| 200                    |
+------------------------+
```

- **示例 2:**

```
输入:
Employee 表:
+----+--------+
| id | salary |
+----+--------+
| 1  | 100    |
+----+--------+
n = 2
输出:
+------------------------+
| getNthHighestSalary(2) |
+------------------------+
| null                   |
+------------------------+
```

:::

## 2. 💻 题解

```

```
