# b4x20221018
B4X實驗: 手機開發.使用Camera Library/CameraEx,製作手機拍照監控功能(B4A),將拍照的照片圖檔傳送到服務器上(B4J)

B4X實驗: 手機開發.使用Camera Library/CameraEx,製作手機拍照監控功能(B4A),將拍照的照片圖檔傳送到服務器上
參考資料:
camera手冊
https://www.b4x.com/android/help/camera.html 
掃條碼功能
https://www.b4x.com/android/forum/threads/b4x-b4xpages-barcode-reader.120417/
網路傳輸
https://www.b4x.com/android/forum/threads/b4x-network-asyncstreams-b4xserializator.72149/#content


1.網路協定採用UDP廣播+TCP連線傳輸
Server: UDP廣播 IP,採用TCP等待連線   (桌面)
Client: 接收UDP廣播,再用TCP連線傳輸  (手機)	

不用手打或者記憶 服務器的IP.連接快速也簡單

2.LIB???權限???

A
3.Camera vs Camera 2.0
Byte() vs Byte 圖形bitmap




4.
TCP Server端 ,新增 每 X 秒判斷是否 在線上

5.exif header 可交換圖檔格式，是專門為數位相機的相片設定的檔案格式，可以記錄數位相片的屬性資訊和拍攝資料。

https://www.b4x.com/android/forum/threads/cameraexclass-save-picture-without-rotation.140947/

关于图片文件旋转JPEG与EXIF信息
https://cloud.tencent.com/developer/article/1531098?from=article.detail.1427939
https://cloud.tencent.com/developer/article/2128476?from=article.detail.1531098


https://github.com/eric19740521/b4x20221018


