# Array
## 基础方法
### concat
> 用于连接多个数组
不改变数组
return 连接后的数组
```js
// arr1.concat(arr2, arr3,...);
var arr1 = [1, 2];
var arr2 = [3, 4];
arr1.concat(arr2); // [1,2,3,4]
arr1; // ([1,2])
```

### join
> 将数组元素放在一个字符串，并用分隔符分割。
不改变数组
return 带连接符的字符串
```js
var arr = [1, 2, 3];
arr.join('-'); // 1-2-3
```

### push（类别unshift）
> 向数组末尾添加一个或多个元素
改变数组
return 数组新长度
```js
var a1 = [1, 2];
var a2 = [3, 4];
a1.push(a2); //  3
```

### pop（类比shift）
> 删除数组最后一个元素，length - 1
改变数组
return 删除的元素

注意：当元素为空时，length不变，返回为`undefined`

### reverse
> 颠倒数组中的元素顺序
改变数组
return 颠倒后的数组

```js
var a1 = [1, 2];
a1.reverse(); // 2, 1
```

### sort
> 对数组元素进行排序
- 无参数：按照字符顺序排列
- 有参数：按照sortby顺序排列

### splice
> 用于插入、删除、替换
```js
array.splice(index, howmany, [ele1,...]); // return 删除的元素
```

### slice
> 返回指定元素
不改变数组
```js
array.slice(start, end); // end 可为负数
```

## 实践
