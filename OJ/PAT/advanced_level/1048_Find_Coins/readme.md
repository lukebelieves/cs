1.  先排序

2.  固定v1，根据key = m - 2，寻找潜在的v2，用二分法寻找上界。

    注意<algorithm>里面的`upper_bound()`，得到的是开区间的上界，即需要将下标`-1`