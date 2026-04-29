# Bubble Sort

這是一個用 Python 實作的冒泡排序（Bubble Sort）程式。

## 功能

- 對整數陣列進行由小到大的排序
- 使用優化過的冒泡排序演算法（當沒有發生交換時提前結束）

## 使用方法

```python
from bubble_sort import bubble_sort

data = [64, 34, 25, 12, 22, 11, 90]
sorted_data = bubble_sort(data.copy())
print(sorted_data)
```

或直接執行：

```bash
python bubble_sort/bubble_sort.py
```

## 執行結果

```
原始陣列: [64, 34, 25, 12, 22, 11, 90]
排序後: [11, 12, 22, 25, 34, 64, 90]
```

## 演算法說明

冒泡排序是一種簡單的排序演算法，它重複地走訪要排序的數列，一次比較兩個元素，如果它們的順序錯誤就把它們交換過來。走訪數列的工作是重複地進行直到沒有再需要交換的元素為止。
