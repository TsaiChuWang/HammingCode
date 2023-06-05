# HammingCode

供NIU1112密碼學期末，非供他用

本專專案目的為實驗[基於漢明碼之數位影像部分可逆式數據隱藏](https://drive.google.com/drive/folders/1dQJ3-2sDr2R-e-_Uuh7sR7_dr5-P7OxN)該篇論文所著內容

內容為實現萊納圖與100張圖像以最大容量分別以LSB,(7,4)Hamming Code,PRDHHC以及[基於漢明碼之數位影像部分可逆式數據隱藏](https://drive.google.com/drive/folders/1dQJ3-2sDr2R-e-_Uuh7sR7_dr5-P7OxN)(後稱該論文)進行數據隱藏分析


## database

內容包含抓下來隨機大小的100張照片以及其後續處理

| folder | illustration |
| :-- | :-- |
|originImage | 原始圖像|
|grayScaleImage | 灰階圖像|
|resizeImage | 修整後的灰階圖像|

ImageData.txt 為紀錄影像名稱的文件

ImageProcess.ipynb 圖像前處理的程式，建議再添加照片到originImage後全部執行一次


