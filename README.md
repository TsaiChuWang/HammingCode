# HammingCode

供NIU1112密碼學期末，非供他用

本專專案目的為實驗[基於漢明碼之數位影像部分可逆式數據隱藏](https://drive.google.com/drive/folders/1dQJ3-2sDr2R-e-_Uuh7sR7_dr5-P7OxN)該篇論文所著內容

內容為實現萊納圖與100張圖像以最大容量分別以LSB,(7,4)Hamming Code,PRDHHC以及[基於漢明碼之數位影像部分可逆式數據隱藏](https://drive.google.com/drive/folders/1dQJ3-2sDr2R-e-_Uuh7sR7_dr5-P7OxN)(後稱該論文)進行數據隱藏分析

執行成功後會得到相對熵，PSNR以及隱藏訊息圖像


## database

內容包含抓下來隨機大小的100張照片以及其後續處理

| folder | illustration |
| :-- | :-- |
|originImage | 原始圖像|
|grayScaleImage | 灰階圖像|
|resizeImage | 修整後的灰階圖像|

ImageData.txt 為紀錄影像名稱的文件

ImageProcess.ipynb 圖像前處理的程式，建議再添加照片到originImage後全部執行一次

## images

存放萊納圖以及前處理圖像，另外有隱藏訊息後圖像

原始萊納圖為

![Lenna](./images/Lenna.jpeg)

## message

隱藏訊息文本

這邊以NIU1112Cryptography及其填充文本為例

## Hamming74

(7,4)Hamming Code的隱藏方法 

該方法參考Image Encoding with Error Correction Ability Using Hamming Code

| file | illustration |
| :-- | :-- |
| database | 隱藏好訊息的的圖像，數量為100 |
| Hamming74.ipynb | 萊納圖測試 |
| Hamming74functional.ipynb | 單一影像的加密以及多張圖片加密與分析 |
| hxx.csv | 100張相對熵(KL散度)的數據紀錄 |
| PSNR.csv | 100張PSNR的數據紀錄 |

![Lenna](./images/Lenna_Hamming74AfterHide.png)

## LSB

最低有效位元 Least Significant Bit, LSB的隱藏方法

| file | illustration |
| :-- | :-- |
| database | 隱藏好訊息的的圖像，數量為100 |
| LSB.ipynb | 萊納圖測試 |
| functuinalLSB.ipynb | 單一影像的加密以及多張圖片加密與分析 |
| hxx.csv | 100張相對熵(KL散度)的數據紀錄 |
| PSNR.csv | 100張PSNR的數據紀錄 |

![Lenna](./images/LennaAfterLSB.jpg)

## PRDHHC

Biswapati Jana, Debasis Giri, Shyamal Kumar Mondal, Partial reversible data hiding scheme using (7, 4) hamming code, Multimed. Tools Appl. 76 (2017) 21691–21706

該論文提出的方案

| file | illustration |
| :-- | :-- |
| database | 隱藏好訊息的的圖像，數量為100 |
| PRDHHC.ipynb | 萊納圖測試 |
| PRDHHCfunctuinal.ipynb | 單一影像的加密以及多張圖片加密與分析 |
| hxx.csv | 100張相對熵(KL散度)的數據紀錄 |
| PSNR.csv | 100張PSNR的數據紀錄 |

![Lenna](./images/lennaGrayScaleCrop.jpg)

## Paper

基於漢明碼之數位影像部分可逆式數據隱藏

該論文提出的方案

作者：彭俊淇 、李志泓 、洪集輝
校院及系所：國立金門大學 電子工程學系
發表於：
第二十一屆離島資訊技術與應用研討會(21 th ITAOI)
地點：Keelung Taiwan
發表時間：Feb. 2022. 

| file | illustration |
| :-- | :-- |
| database | 隱藏好訊息的的圖像，數量為100 |
| Paper.ipynb | 萊納圖測試 |
| Paperfunctuinal.ipynb | 單一影像的加密以及多張圖片加密與分析 |
| hxx.csv | 100張相對熵(KL散度)的數據紀錄 |
| PSNR.csv | 100張PSNR的數據紀錄 |

![Lenna](./images/lennaGrayScaleCrop.jpg)

## summary

數據總分析的部分