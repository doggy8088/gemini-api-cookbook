# Gemini 檔案 API 範例客戶端程式碼

## 背景
Gemini 檔案 API 提供開發人員一個簡單的方式來上傳檔案並在多模態情境中使用 Gemini API。這個存放庫展示了如何使用檔案 API 上傳圖片並將其包含在對 Gemini API 的 `GenerateContent` 呼叫中。

> [!IMPORTANT]
> 檔案 API 目前處於測試版，僅在[特定地區](https://ai.google.dev/available_regions)提供。

## 快速入門
準備好開始了嗎？學習如何上傳檔案並在 Gemini API 的 GenerateContent 請求中使用它們的基本要點：

[檔案 API Colab](https://github.com/google-gemini/cookbook/blob/main/quickstarts/File_API.ipynb)

[音訊 Colab](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Audio.ipynb)

[影片 Colab](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Video.ipynb)

## Python 範例
```
# Prepare a virtual environment for Python.
python3 -m venv venv
source venv/bin/activate

# Add API key to .env file
touch .env
echo "GOOGLE_API_KEY='YOUR_API_KEY'" >> .env

# Install dependencies.
pip3 install -U -r requirements.txt

# Run the sample code.
python3 sample.py
```

## Node.js 範例
```
# Make sure npm is installed first.

# Add API key to .env file
touch .env
echo "GOOGLE_API_KEY='YOUR_API_KEY'" >> .env

# Install dependencies.
npm install

# Run the sample code.
npm start
```

## cURL Bash Script 範例
以下腳本將根據檔案路徑上傳檔案。
```
bash ./sample.sh -a "<YOUR_KEY>" -i "sample_data/gemini_logo.png" -d "Gemini logo"
```
