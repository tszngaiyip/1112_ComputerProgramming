1) 製作處理字串的class, mString
2) 製作小型的編碼機的class, mCipher

- 編碼解碼方法在Test_Cast.txt，內有詳細說明並附有範例

- 對應表有分為Rotor和Reflector
- 編碼 Encode：依序輸入原始文字並得到對應的加密內容
- 解碼 ：依序輸入加密過的字元得到原始文字

動態模式：
- 重設編碼機狀態：reset()
- 每次輸入一個字元，Rotor和輸入輸出的對應就會改變

總結：
- 靜態模式下，在設定好機器後，每一個輸入會穩定得到一個固定輸出。因此解碼只要將密文再輸入一次即可。
- 動態模式下，在設定好機器並重設旋轉量後，每一次輸入對應到的輸出都會變，但他的變動有規律。所以拿到密聞後，只要重新設定旋轉量，依序將密文輸入即可得到原始輸入。




