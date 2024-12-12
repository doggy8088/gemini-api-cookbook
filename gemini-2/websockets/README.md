# Gemini 2.0 Cookbook

這是一個專門針對 websocket 的範例和快速入門集合，用於使用 **實驗性** 的 Gemini 2.0 Flash 模型。

Python 使用者應該使用 [Google GenAI SDK](https://ai.google.dev/gemini-api/docs/sdks) 來建構以存取多模態即時 API，但由於底層 API 是通過安全的 websockets 提供的，以下範例已提供以幫助您了解協議的運作方式。

要了解 2.0 模型版本中的新功能和新的 [Google GenAI SDKs](https://github.com/googleapis/python-genai)，請查看 [Gemini 2.0 模型頁面](https://ai.google.dev/gemini-api/docs/models/gemini-v2)。要立即開始實驗該模型，請前往 [Google AI Studio](https://aistudio.google.com/prompts/new_chat?model=gemini-2.0-flash-exp) 進行提示或前往 [多模態即時 API 展示](https://aistudio.google.com/live) 試用新的即時功能。
## 目錄

在您自己的本地機器上探索 Gemini 2.0 的功能。

* [即時 API 入門腳本](./live_api_starter.py) \- 一個使用 websockets 的本地可執行 Python 腳本，支持從您的機器串流音訊進出

通過以下可以在 Google Colab 上執行的筆記本探索 Gemini 2.0 的功能。

* [即時 API 入門](./live_api_starter.ipynb) \- 使用 websockets 的多模態即時 API 概述
* [即時 API 工具使用](./live_api_tool_use.ipynb) \- 使用 websockets 的即時 API 工具使用概述