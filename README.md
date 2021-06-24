## 🐶摘要說明  
利用自定義的資料集進行寵物行為辨識，從定義動作來了解寵物需求或是達到遠端監控寵物  
主要辨識的動作為一般常見的站、坐、臥，以外的動作可能就是非正常情況下會出現的，需要多加注意。  

模型選用準確度及運算速度都很強大的YOLOv3，不僅這樣也方便部署在監視器或是EdgeAI 上，完成商品化及泛化。  


## 🐶創意發想  
有鑑於寵物獨自在家，可能會造成危害或是其他災難，採用動作辨識的方式  
可以察覺寵物是否再進行異常的行動或行為，防止或降低寵物的破壞家中家具
除此之外，也能在不在家的時候照護寵物，達到即時反應的功能。  

## 🐶Keras YOLO Local使用說明
1. 利用git colne 下載檔案或是直接下載zip 檔
2. 可直接使用下方的訓練完權重檔進行推論 
若須重新訓練及其他詳細說明可參考：[HackMD公開文檔](https://hackmd.io/LTaOjgeXQAutqN3GzwFoJQ?view)

## 🐶Colab使用說明
1. 將影像檔及標註檔先下載到自己的雲端硬碟
2. 影像檔及標註檔會解壓縮到Colab 裡
3. 執行其他的cfg 檔案及Darknet 下載 
4. 訓練模型權重會放置在雲端硬碟裡的 pet_dection_on_colab/weight
5. 訓練完模型後即可測試結果


## 🐶權重檔及相關資料集  
訓練完的權重檔：https://drive.google.com/file/d/13QQEtiDuASWu965kjZPpbMEx2Qb4C_Tk/view?usp=sharing  
資料集影像檔：https://drive.google.com/file/d/1Uxde2Y0sC911iNO4oxjNMiWy2ymqsuCy/view?usp=sharing  
資料集標註檔：https://drive.google.com/file/d/1JSNO4ovHb_jPUiqDSGq9CPZeAoIpLZys/view?usp=sharing 

![圖示](https://github.com/joyqoo/pet_dection_on_colab/blob/72296c0f09b44bed6959e38751440aa57f05b436/cover_picture.png)
  
