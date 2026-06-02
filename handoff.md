# 九九乘法挑戰賽 — 交接文件

## 這次做了什麼
1. **足球牌改版** — 移除藍色圓形底圖，讓 ⚽ emoji 直接以大字顯示（`font-size:4.5rem`，背景透明）
2. **翻牌數字加大** — `.card-circle` 字體從 `0.95rem` 調大至 `1.3rem`
3. **入場券 → 蝴蝶餅** — 所有 coin pill 的 `🎟️` 改為 `🥨`
4. **幸運餅乾** — coinAnim 動畫文字從「獎券」改為「幸運餅乾」
5. **檔案損壞修復** — PowerShell 編碼操作導致中文全部損壞，重新完整寫入 `99chill.html`

## 修改的檔案
- `99chill.html`（唯一檔案，單頁應用）

## 下次從哪裡接手
- 遊戲功能完整，所有 5 頁皆正常運作
- 無待辦功能，等待 Chi 的新需求

## 已知問題 / 注意事項
- **無 git repo**，沒有版本控制，檔案損壞時只能重寫
- PowerShell 5.1 對 UTF-8 中文檔案的字串替換有編碼風險，**必須用 Edit 工具替換，不可用 PowerShell**
- localStorage key 為 `'99chill'`，測試時可用 `localStorage.clear()` 重置存檔
