Quick Start
===========
這個雲端資料夾存放每次的題目、練習的問題回顧與資料整理，方便在任何裝置查看、更新檔案

## 資料整理方式
每個**子資料夾**皆為一次上課的重點整理，命名規則為「 **mmdd** 」，內部存放無須下載、可直接閱讀的 Markdown 格式檔案 (**.md**)，及轉成可下載列印的 PDF 格式檔案 (**mmdd.pdf**)。整體結構如下：

```
Music Theory Review/
├─ 1031/
│  ├─ 1031.pdf
│  └─ README.md
├─ 1107/
│  ├─ 1107.pdf
│  └─ README.md
├─ ...
└─ README.md (本說明文件)
```

## 操作方式
- **查看**：點開欲察看日期的資料夾，內容會直接顯示在頁面下方
- **下載**：進入資料夾後**點選 PDF 檔案**，下載按鈕會在 **PDF 內容右上方**
- **編輯**：由於編輯權限未對外開放，僅能下載到裝置做本地端編輯。建議使用 **VS Code (Windows)** 或 **XCode (MacOS)** 做編輯，實作步驟大同小異，此處以 Windows 系統為例：
    1. 點開此頁面頂部 **綠色「<> Code」按鈕**，並**複製**該連結
    2. 按下 `Win + R` 按鈕，輸入 `cmd` 並按下 `Enter` 進入終端
    3. 輸入 `git clone 複製的連結` 下載
    4. 下載並安裝 [Visual Studio Code](https://code.visualstudio.com/)
    5. 開啟 VS Code -> 點選左上角 **File** -> **Open Folder** -> 在 `C:\users\USER` 資料夾找到 `Music-Thoery-Review` 資料夾 -> 點擊該資料夾並點選 `選擇資料夾`
    6. 在左側的面板點選要編輯的檔案 (**.md**)，即可修改編輯
    7. 修改完成後，按下 `Ctrl + S` 存檔