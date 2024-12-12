# Gemini 2.0 Cookbook

這是一個使用 **實驗性** [Gemini 2.0 Flash](https://ai.google.dev/gemini-api/docs/models/gemini-v2) 模型的範例和快速入門集合。

要了解 2.0 模型版本中的新功能和新的 [Google GenAI SDKs](https://github.com/googleapis/python-genai)，請查看 [Gemini 2.0 模型頁面](https://ai.google.dev/gemini-api/docs/models/gemini-v2)。要立即開始實驗該模型，請前往 [Google AI Studio](https://aistudio.google.com/prompts/new_chat?model=gemini-2.0-flash-exp) 進行提示或前往 [多模態即時 API 展示](https://aistudio.google.com/live) 試用新的即時功能。

## 目錄

通過以下可以在 Google Colab 上執行的筆記本探索 Gemini 2.0 的功能。

* [入門](./get_started.ipynb) \- 使用 GenAI SDK 的綜合概述
* [即時 API 入門](./live_api_starter.ipynb) \- 使用 GenAI SDK 的多模態即時 API 概述
* [即時 API 工具使用](./live_api_tool_use.ipynb) \- 使用 GenAI SDK 的即時 API 工具使用概述
* [繪圖和映射](./plotting_and_mapping.ipynb) \- 展示搜尋、程式碼和函式呼叫的範例
* [搜尋工具](./search_tool.ipynb) \- 使用 GenAI SDK 的單一和即時 API 的快速入門
* [空間理解](./spatial_understanding.ipynb) \- 使用 GenAI SDK 的 2D 空間理解功能的綜合概述
* [空間理解 (3D)](./spatial_understanding_3d.ipynb) \- 使用 GenAI SDK 的 3D 空間理解功能的綜合概述

或者在您自己的本地機器上探索。

* [即時 API 入門腳本](./live_api_starter.py) \- 一個使用 GenAI SDK 的本地可執行 Python 腳本，支持從您的機器串流音訊進出

也可以在 [`websockets`](./websockets/) 目錄中找到專門針對 websocket 的範例。