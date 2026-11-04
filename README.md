# Daily English Coach

每天 10 分鐘的職場英文口說練習（Warm-up → Learn → Practice → Apply 角色扮演），單一 HTML、無建置、無伺服器。
網址：https://caco3naoh-rf.github.io/daily-english-coach/

## 設定（每台裝置各做一次）

1. 打開網址 →「我」→〈連線設定〉。
2. **Gemini API key**（AI 家教）：aistudio.google.com → Get API key → Create API key，貼上 →「儲存並測試」。
3. **GitHub token**（手機電腦同步進度）：GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic) → Generate，只勾 `gist`，貼上 →「儲存並測試」。進度存在你帳號的一個私人 Gist（`daily-english-coach.json`），第二台裝置貼同一把 token 就會接上。

key 與 token 只存在該裝置的瀏覽器（localStorage），不會進 Gist、網址或這個 repo。兩個都不設也能用：沒有 Gemini key 時用自評模式，沒有 token 時進度只存在本機。
