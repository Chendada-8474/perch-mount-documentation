
# Media Status

## Definition

- Undetected: 剛上傳到資料庫的資料，還正在等待 AI Detector 的自動辨識。
- Unchecked: AI 辨識完，沒有偵測到個體的資料。正在等待使用者做空拍檢查。
- Unreviewed: AI 辨識完，有偵測到個體的資料，或者是使用者在做空拍檢查的時候發現有個體但 AI 沒有發現。正在等待使用者檢視物種，或者是增加個體。
- Reviewed: 使用者檢視完物種。
- Accidental: 經過使用者確認後確認沒有個體的資料，這筆資料的影像檔案會在確認後被刪除。


## Work Flow
![Architecture](./statics/media_status.png)