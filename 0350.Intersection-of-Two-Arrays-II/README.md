Difficulty: Easy

# 解题思路
用map存储第一个数组中的元素和元素出现的次数，然后遍历第二个数组，检查是否在map中存在，如果存在，
则将该元素加入结果数组中，并把对应的次数减一，如果对应的次数等于0，则删除map中的该元素