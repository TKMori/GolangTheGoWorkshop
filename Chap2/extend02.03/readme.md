# 學習重點

1. 氣泡排序法是透過陣列內元素倆倆比較來慢慢決定出排序的方法

2. 每次排序會決定出最右邊的數值，以此類推，最大比較次數是整個陣列的長度 -1 (n - 1)

3. 可透過雙層 for 迴圈來實現，最外層決定現在是第幾 round，內層實際去做數值的比較