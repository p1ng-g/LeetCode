Difficulty: Easy

# 解题思路
朴素解法：

直观的解法的是：枚举原串 ss 中的每个字符作为「发起点」，每次从原串的「发起点」和匹配串的「首位」开始尝试匹配：
- 匹配成功：返回本次匹配的原串「发起点」。
- 匹配失败：枚举原串的下一个「发起点」，重新尝试匹配。

KMP：
