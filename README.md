# 臉部色彩分析系統

本專案使用 Python、dlib 和 Gemini AI 進行圖片及人臉色彩分析。

## 系統需求
- Python 3.9+
- dlib 人臉特徵模型
- Gemini API 金鑰

## 主要功能
- **圖片分析**：使用 analyzer.py 進行圖片處理與分析
- **人臉檢測**：透過 face_detection.py 實現人臉辨識
- **特徵提取**：face_extraction.py 負責提取人臉特徵
- **季節判定**：season_type.py 進行個人色彩季節判定


## 安裝步驟
1. 安裝必要套件
   ```bash
   pip install -r requirements.txt

2.準備必要檔案
下載 shape_predictor_68_face_landmarks.dat
放置於專案根目錄

3.設定環境變數
複製 .env.example 為 .env
設定 Gemini API 金鑰



## 功能說明
- 圖片上傳與處理
- 人臉偵測與特徵提取
- 個人色彩分析
- AI 輔助判定

## 注意事項
- API 金鑰已設定在 .gitignore 中
- 模型檔案不納入版本控制
- 檢查 .env 檔案是否正確設定
