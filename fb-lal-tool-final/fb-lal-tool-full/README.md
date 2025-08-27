
# FB Lookalike Audience Tool (完整版)

用 Streamlit 建立的批量 Facebook 類似受眾建立工具。

## 使用方式

### 本機測試
1. 安裝依賴
   ```bash
   pip install -r requirements.txt
   ```

2. 建立 `.streamlit/secrets.toml` 檔案：
   ```toml
   [secrets]
   fb_access_token = "YOUR_FACEBOOK_ACCESS_TOKEN"
   ```

3. 執行：
   ```bash
   streamlit run app.py
   ```

### 部署到 Streamlit Cloud
1. 登入 <https://share.streamlit.io>  
2. 點 **New App** → 選擇 GitHub repo → Branch: main → File path: `app.py`  
3. 進入 **App → Edit secrets**，貼上：
   ```toml
   [secrets]
   fb_access_token = "YOUR_FACEBOOK_ACCESS_TOKEN"
   ```
4. 儲存後 App 會自動重啟，即可使用。
