# Least Significant Bit

# 獲取要隱藏的訊息

1. 逐字讀取原始訊息
2. 轉換為ascii碼
3. ascii碼轉換為二進制(0bxxxxxxx)的字串
4. replace()替換0b為空
5. 七位數二進制填充為八位數

## Reference

[1] [Steganalysis](https://github.com/librauee/Steganalysis/blob/master/LSB/hide_info.py)