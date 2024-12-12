解题需要注意：第一这是一个有序数组，第二原地修改。

因为是原地修改，所以我们不能使用额外的空间，只能使用数组本身的空间。
因为是有序数组，所以我们只需要考虑当前元素于前一个元素是否相同。

本题采用双指针法，一个指针指向原始数组，另一个指针可以理解为指向未来我们删除重复元素之后的数组。
假设a指针指向原始数组，b指针指向未来数组。a指针每次移动一步，如果当前元素与前一个元素不同，则将当前元素赋值给b指针指向的未来数组。

只需要注意第一个元素一定是单一元素，不能删除。