# 1.Python小技巧

## 1.1 对二维数组的遍历

```python
a = [[7,7],[1,2],[9,7],[7,3],[3,10],[9,8],[8,10],[4,3],[1,5],[1,5]]
# 使用下面的代码可以遍历a,i代表a[:][0], a[:][1]
# 其中，a[::-1]代表逆序
for i, j in a[::-1]:
```

## 1.2 python关键字排序

```python
# 对a排序，有限a[0], 然后a[1]
a.sort(key=lambda x:(x[0], x[1]))
# 对a排序，关键字x[0], 逆序输出
a.sort(key=lambda x:x[0], , reverse=True)
```

