# Human First — AI_FIRST 轉型成果分享

> 這個 repo 用來集中收錄 **AI_FIRST 轉型成果分享**（2026-06-10）各團隊的成果，並延續後續可以投入開發的議題。
> 不論是投影片、專案介紹、架構，或可重用的技術檔（SKILL / SCRIPT / prompt / 設定檔），都歡迎上傳分享。

---

## 📤 怎麼上傳你的成果（四步驟）

1. **複製範本** — 把 `projects/_TEMPLATE/` 整個資料夾複製一份
2. **改名** — 改成你的專案名稱，建議用英數小寫加連字號，例如 `qt-auto-test`、`tx-doc-gen`
   - 路徑會變成 `projects/你的專案名/`
3. **填寫介紹** — 編輯該資料夾內的 `README.md`，把欄位填好
4. **放檔案** — 把對應檔案放進三個子資料夾：

| 子資料夾 | 放什麼 |
|---|---|
| `slides/` | 投影片（建議匯出 **PDF**，相容性最好；原始 pptx / keynote 可一併附上） |
| `architecture/` | 架構圖、流程圖、系統簡介文件（png / svg / md） |
| `skills-scripts/` | 可重用的技術產物：Claude/Cursor **SKILL**、自動化 **SCRIPT**、prompt、設定檔，附簡短使用說明 |

> 不熟 git 也沒關係：可以直接在 GitHub 網頁上，進到資料夾按 **Add file → Upload files** 拖拉上傳。

---

## 🗂️ 資料夾結構

```
Human_First/
├── README.md                  ← 你正在看的這份
└── projects/
    ├── _TEMPLATE/             ← 範本，複製整包改名後使用
    │   ├── README.md          ← 專案介紹（填表）
    │   ├── slides/            ← 投影片
    │   ├── architecture/      ← 架構與介紹
    │   └── skills-scripts/    ← SKILL / SCRIPT 等技術檔
    └── 你的專案名/             ← 每個專案一個資料夾（扁平分類）
```

---

## 📌 命名與檔案建議

- 專案資料夾名稱：英數小寫 + 連字號（`-`），避免空格與特殊符號，方便連結與跨平台
- 大型檔案（影片、超過 ~50MB 的二進位檔）建議**放雲端連結**，不要直接 commit
- 內含機密 / 客戶資料的內容，上傳前請先去識別化

---

## 💬 後續延伸議題與互動

- **🧪 Issue：AI自動化測試** — 這是轉型後想持續延伸投入的議題，歡迎在 [Issues](../../issues) 一起討論工具選型、導入經驗、可共用的測試框架／SKILL 與下一步。
- **🤝 Discussion：成果應用申請** — 對某個上傳的專案有興趣、想實際導入的人，到 [Discussions](../../discussions) 的「成果應用申請」分類登記，由原作者協助你落地。
