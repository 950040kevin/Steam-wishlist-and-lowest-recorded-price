# Steam-wishlist-and-lowest-recorded-price
使用Github Action 執行python，將Steam願望清單中特價中的遊戲與其歷史最低價做統整，傳送到Discord。

# 教學
1.將所有檔案複製到自己的 Github Repositories

2.將 Steam wishlist 改成公開，並把 main.py 第31行的網址進行更改

3.在 Repositories 的 Settings -> Secrets and variable -> Actions 建立 Secrets：
  - Name: DISCORD_WEBHOOK_URL, Secret: **輸入 Discord webhook 網址**
  - Name: ZENROWS_PROXY, Secret: **輸入 proxy 引號中的內容**

4.將 schedule.yml 第5行的自動執行時間改成想要的時段
