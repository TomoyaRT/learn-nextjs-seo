參考教學：https://www.youtube.com/watch?v=wTGVHLyV09M

1. 設定 favicon.ico
-> 工具：https://realfavicongenerator.net/

2. 設定 Open Graph
-> Doc：https://nextjs.org/docs/app/api-reference/file-conventions/metadata/opengraph-image#opengraph-image

3. 設定 app/layout 的 Metadata
-> Doc：https://nextjs.org/docs/app/api-reference/functions/generate-metadata

4. 設定 page 的 Metadata
-> Doc：https://nextjs.org/docs/app/api-reference/functions/generate-metadata

5. 設定指定社群軟體的Metadata  例如 Twitter

6. 確認連結的顯示介面
-> 透過 TLS 在線上公開本地服務 https://docs.srv.us/
-> 確認各大社群媒體的連結 https://www.opengraph.xyz/

7. 設定 sitemap -> 告知搜尋引擎網站中所有重要的頁面。(URL,最後修改時間,變更頻率,頁面優先級別)。 

8. 設定 robots.txt -> 設定網站的訪問規則

------------ 更細緻的SEO優化(AI建議) ------------

9. 優化網站速度
壓縮圖片：使用壓縮工具（如 TinyPNG 或 ImageOptim）減少圖片的大小。
Lazy Loading：啟用圖片延遲載入，減少初次頁面載入時的資源使用量。
優化代碼：減少 CSS、JavaScript 檔案的大小並使用 CDN 分發資源。

10. 增加 Schema Markup
使用 Schema Markup（結構化資料）：例如 FAQ、文章、產品等 schema，這樣可以讓搜尋引擎更好地理解網站內容，並在搜尋結果中以豐富摘要（rich snippets）的形式展示。
測試工具：使用 Google 的結構化資料測試工具來確認標記是否正確。

11. 設置內部連結策略
內部連結：適當地在頁面內增加到其他相關頁面的連結，提升使用者在網站內的瀏覽深度，也有助於搜尋引擎理解網站結構。
確保連結的關鍵字：在連結的文字中使用目標頁面的關鍵字，提升該頁面在相關關鍵字的排名。

12. 建立與目標關鍵字相關的高品質內容
關鍵字研究：使用工具（如 Google Keyword Planner 或 Ahrefs）找出用戶關注的關鍵字，並在內容中適度使用。
內容長度與質量：創建詳細且有價值的內容，並且使用分段、標題、圖片等來提升可讀性。

13. 管理與提升反向連結（Backlinks）
獲取高品質反向連結：尋求相關網站的連結，這有助於提升網站的權重。
避免低質量的連結：監控網站的反向連結品質，避免來自垃圾網站或不相關網站的連結，以免影響排名。

14. 提升行動裝置友好性
行動裝置優化：確保網站在行動裝置上有良好的使用者體驗，避免文字過小、按鈕過近、圖片未調整等問題。
Google 行動裝置相容測試：使用 Google 的行動裝置相容測試工具 來檢查網站的行動裝置優化情況。

15. 優化網站的 Core Web Vitals
主要性能指標：包括 LCP（Largest Contentful Paint）、FID（First Input Delay）和 CLS（Cumulative Layout Shift），這些都是 Google 用於衡量使用者體驗的重要指標。
改善工具：使用 Google PageSpeed Insights 或 Lighthouse 來檢測這些指標，並根據建議進行改善。

16. 設定 404 和 301 重定向
404 頁面：設計友好的 404 頁面，幫助使用者重新找到所需內容。
301 重定向：將刪除或搬遷的頁面設置為 301 重定向，避免壞連結影響 SEO。

17. 啟用 SSL 並強制 HTTPS
安全性：確保網站的所有頁面都在 HTTPS 上運行，增加使用者信任並提升搜尋排名。
重定向：將 HTTP 自動重定向到 HTTPS，以確保搜尋引擎只索引 HTTPS 版本。

18. 設定 Google Search Console 與 Google Analytics
網站健康檢查：透過 Google Search Console 瞭解網站的健康狀況（如索引狀態、錯誤等）。
數據追蹤：使用 Google Analytics 分析流量來源、使用者行為等數據，以便調整 SEO 策略。
這些步驟不僅能進一步提升網站的 SEO 成效，也能幫助提升使用者體驗，增加網站的整體排名表現。

------------ 課程補充部分 ------------

1. 靜態頁面渲染速度快 對SEO友好

2. fetch 會自動 cache 相同請求，如果不使用 fetch 可以改用 react cache 的方式去做。

3. 善用 generateStaticParams 提早生成靜態頁面，避免不必要的請求。(如果數量過多可以選擇生成前100筆資料也可以。)



