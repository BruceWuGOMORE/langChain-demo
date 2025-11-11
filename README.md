# 🚀 LG-DEMO 專案指南

歡迎使用 `lg-demo` 專案！本指南將引導您完成專案的環境設置、配置和啟動流程。

## 📦 專案儲存庫

您可以透過以下連結獲取本專案的程式碼：

[**GitHub 儲存庫：https://github.com/ryvn-gm/lg-demo**](https://github.com/ryvn-gm/lg-demo)

---

## 🔑 先決條件 (Prerequisites)

本專案運行依賴於以下兩項外部服務的 API Key：

1.  **Tavily API Key:**
    * 來源：[https://app.tavily.com/](https://app.tavily.com/)
2.  **LangSmith API Key (Observability):**
    * 來源：[https://www.langchain.com/langsmith/observability](https://www.langchain.com/langsmith/observability)

---

## 🛠️ 環境配置與啟動

請按照以下步驟，依序配置並啟動專案的後端與前端環境。

### 步驟 1: 配置 API Keys

請在專案根目錄下的 **`.env`** 檔案中，配置所有必要的 API Keys（請注意檢查文件中有兩處需要配置）：

```env
# 範例 (請替換為您的實際 Key)
OPENAI_API_KEY=sk-proj-QVQ49rgjjlCZOUDSVxASNahe4VsJbvEOsBDCDMPVr_vRdUrBGTkDE_pWA1s0Ux0W2XtGtB984T3BlbkFJwJWSgDoyGxuhfzaPc3QXwC2ukzR7dsq9LJNcH9F2BMiyXc66123QvkWv1T0MdAOMsVcVJEcXgA

# 確保同時配置 LangSmith 和 Tavily 的 Key
TAVILY_API_KEY=...
LANGSMITH_API_KEY=...
