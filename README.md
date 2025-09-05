# 🤖✍️ AI 專業 SEO 標題產生器 (Google Colab 版)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vvchung/ollama_colab_stable_seo_generator/blob/main/ollama_colab_stable_seo_generator.ipynb)

<br>

還在煩惱文章標題怎麼下嗎？想用最新的大型語言模型（LLM）又不想處理複雜的環境設定或支付昂貴的 API 費用嗎？

這個專案就是你的完美解決方案！🎉

我們提供一個 Google Colab 筆記本，讓你**完全免費**、**一鍵啟動**一個由 `Ollama` 和 `Llama 3` 驅動的 AI 標題產生器，專門為你生成高品質、符合 SEO 規範的殺手級標題！

<br>

## ✨ 核心亮點

*   **🤑 完全免費運行**：在 Google Colab 的免費方案中，體驗強大的 Ollama 和 Llama 3 模型，無需任何花費。
*   **🚀 一鍵啟動**：拋開繁瑣的本地端環境設定！只要依序執行 Colab 儲存格，即可擁有你的 AI 寫手。
*   **🧠 專業 Persona 提示**：我們精心設計了一個「擁有10年經驗的專業 SEO 標題產生者」Prompt，讓 AI 不僅是生成文字，更是以專家思維進行創作。
*   **🔗 整合 LangChain**：使用業界最流行的 LangChain 框架，輕鬆打造 LLM 應用，程式碼結構清晰易懂。
*   **🔧 穩定可靠**：採用了更穩定的 Python 背景執行緒方法，有效解決了在 Colab 中常見的 Ollama 伺服器連線失敗問題。

<br>

## 📝 如何使用？超級簡單三步驟！

1.  **🖱️ 點擊上方 "Open in Colab" 徽章**
    *   它會直接在你的瀏覽器中打開這個 Google Colab 筆記本。

2.  **▶️ 從上到下，依次執行每個儲存格**
    *   點擊每個程式碼區塊左邊的「播放」按鈕。
    *   **⏳ 請耐心等候！** 第 3、4 格會需要幾分鐘來下載 Ollama 和 Llama 3 模型，這是正常的喔！

3.  **✏️ 輸入你的關鍵字，見證奇蹟！**
    *   在最後一個儲存格中，找到 `input_keyword` 變數。
    *   將它改成任何你想要操作的核心關鍵字（例如：`"數位孿生"`）。
    *   執行它，AI 就會立刻為你生成 5 個專業的 SEO 標題！

<br>

## 🛠️ 技術堆疊

| 技術 | 用途 |
| :--- | :--- |
| **Google Colab** | 💻 提供免費的雲端運算環境 |
| **Ollama** | 📦 在 Colab 中輕鬆運行開源 LLM |
| **Llama 3** | 🧠 提供強大的自然語言生成能力 |
| **LangChain** | 🔗 串連 Prompt、模型與輸出的框架 |
| **Python** | 🐍 實現這一切的魔法語言 |

<br>

## 🧙‍♂️ 成功的秘密：專業的 Prompt 設計

這個 AI 之所以能產出高品質的標題，關鍵在於我們賦予它的「角色」。在 Prompt 中，我們明確定義了它的身份、任務，以及必須遵守的 **SEO 技術要求**和**文案創意要求**：

*   **技術面**：關鍵字位置、標題長度、數字/疑問詞使用...
*   **創意面**：點擊率、價值傳達、目標受眾...

這就是 Prompt Engineering 的魅力！

<br>

## 🙏 特別感謝

這個專案能夠在 Colab 中穩定運行，主要參考了以下文章提供的寶貴方法：

*   [My APOLLO - Google Colab 也能跑 Ollama - 教學](https://www.myapollo.com.tw/blog/google-colab-ollama/)

<br>

---

覺得這個專案有趣嗎？給它一個 ⭐ Star 吧！如果你有任何問題或建議，也歡迎提出 Issue 交流！
