# Bubble Sort

一個用 Python 實作的冒泡排序（Bubble Sort）演算法專案。

## 功能特點

- ✅ 對整數陣列進行由小到大排序
- ✅ 優化過的冒泡排序演算法（加入提前終止機制）
- ✅ 簡潔易懂的程式碼實作
- ✅ 包含可直接執行的範例

## 演算法說明

冒泡排序（Bubble Sort）是一種簡單的排序演算法，其運作方式如下：

1. 比較相鄰的兩個元素
2. 如果第一個比第二個大，就交換它們
3. 對每一對相鄰元素做同樣的工作，從開始第一對到結尾的最後一對
4. 重複以上步驟，直到沒有任何一對數字需要比較

**優化特性**：當某一輪走訪中沒有發生任何交換時，表示陣列已經排序完成，演算法會提前結束，避免不必要的比較。

## 時間複雜度

| 情況 | 時間複雜度 |
|------|-----------|
| 最佳情況（已排序） | O(n) |
| 平均情況 | O(n²) |
| 最差情況（反向排序） | O(n²) |

空間複雜度：O(1)（原地排序）

## 安裝與使用

### 前置需求

- Python 3.x

### 使用方法

**方法一：作為模組匯入**

```python
from bubble_sort.bubble_sort import bubble_sort

data = [64, 34, 25, 12, 22, 11, 90]
sorted_data = bubble_sort(data.copy())
print(sorted_data)  # [11, 12, 22, 25, 34, 64, 90]
```

**方法二：直接執行**

```bash
python bubble_sort/bubble_sort.py
```

執行結果：
```
原始陣列: [64, 34, 25, 12, 22, 11, 90]
排序後: [11, 12, 22, 25, 34, 64, 90]
```

## 專案結構

```
bubble-sort/
├── bubble_sort/
│   ├── bubble_sort.py    # 主要排序程式
│   └── README.md         # 子目錄說明文件
└── README.md             # 本文件
```

## 貢獻

歡迎提出問題（Issues）和拉取請求（Pull Requests）來改進這個專案！

## 授權

本專案採用 MIT 授權條款。

---

**作者**：Nickh2k6  
**GitHub**：https://github.com/Nickh2k6/bubble-sort
