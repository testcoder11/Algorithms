|  | 递归式  |解决方案  | 应用实例 |
|:-|
|1| T(n)=T(n-1)+1 |O(n)   |序列化处理|
|2| T(n)=T(n-1)+n |O(n**2)|握手问题|
|3| T(n)=2T(n-1)+1|O(2**n)|汉诺塔问题|
|4| T(n)=2T(n-1)+1|O(2**n)|      |
|5| T(n)=T(n/2)+1 |O(lgn) |二分搜索|
|6| T(n)=T(n/2)+n |O(n)   |随机选择问题|
|7| T(n)=2T(n/2)+1|O(n)   |树的遍历|
|8| T(n)=2T(n/2)+n|O(n)   |利用分治进行排序|