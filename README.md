# MNIST 手寫數字分類：CNN 課堂實作

本專案使用 PyTorch 建立卷積神經網路，辨識 MNIST 手寫數字。原始訓練資料分為 54,000 張 Training 圖片與 6,000 張 Validation 圖片，並以獨立的 10,000 張 Test 圖片進行最終評估。模型包含卷積、ReLU、池化及全連接層，使用 CrossEntropyLoss 與 Adam 訓練 10 個 epochs，依 Validation accuracy 儲存最佳模型。Notebook 展示資料樣本、各層輸出形狀、訓練曲線、各數字的分類正確率，以及測試圖片的預測結果。本次執行的整體 Test accuracy 為 **99.07%**。執行 `[5115056028]CNN課堂練習.ipynb` 時，程式會自動下載 MNIST 資料。