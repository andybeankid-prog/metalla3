# FB Lookalike Audience Tool

用 Streamlit 建立的批量 Facebook 類似受眾建立工具。

## 使用方式

1. 安裝依賴
   ```bash
   pip install -r requirements.txt
   ```
2. 新增 `.streamlit/secrets.toml`
   ```toml
   [secrets]
   fb_access_token = "YOUR_FACEBOOK_ACCESS_TOKEN"
   ```
3. 啟動
   ```bash
   streamlit run app.py
   ```
