## 指令 (預設為黑名單模式)

*注意: 以下指令都沒有設定任何權限限制，任何人都能使用。*

- 黑名單模式(預設)
    - blockchannel ➡️ 新增頻道至黑名單
    - unblockchannel ➡️ 將頻道從黑名單移除
- 白名單模式
    - openchannel ➡️ 新增頻道至白名單
    - closechannel ➡️ 將頻道從白名單移除
- reset ➡️ 清空頻道短期記憶

## 注意事項
- 以上指令皆為前綴指令。
- 指令在私訊 (DM channel) 無法使用。
- 這個版本是 **每則訊息都會回覆**，**不需要 mention (@)**，所以一次太多訊息他會卡住。
- 此機器人不會回應其他機器人之訊息。
- **每個頻道的短期記憶是分開的**，reset 指令只會清空指定頻道的短期記憶。
- 短期記憶的上限包含機器人的回覆。
- 短期記憶僅包含文字回應，不包含圖片回應。
- 如果 config.json 中 mode 填寫的不是 blacklist 或 whitelist，會導致機器人無法使用指令。