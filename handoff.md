# 九九乘法挑戰賽 — 交接文件

## 這次做了什麼（2026-06-06）

### 刪除鍵倒數秒數調整
- 初級按刪除後重設為 7 秒
- 中級按刪除後重設為 4 秒
- 高級按刪除後重設為 3 秒（不變）

### 快問快答暫停功能（新增）
- 每關限暫停 3 次，按鈕顯示剩餘次數
- 按暫停：倒數停止、題目完全遮蓋（不透明）
- 遮罩內顯示玩家角色 + 最新解鎖動物獎章左右走動並上下跳躍動畫
  - 兩角色各佔左右半邊，同步靠近又分開，錯開跳躍節奏
- 按「▶ 繼續挑戰」恢復倒數與題目
- 用完 3 次後按鈕變灰不可按

### 幸運餅乾浮字調整
- 字級從 1.3rem 加大至 1.8rem
- +3 顏色改為藍綠色 #00AEAE

## 修改的檔案
- `index.html`

## 下次從哪裡接手
- 遊戲已上線：https://elain-chi.github.io/99chill
- 遊戲說明文字 Chi 要修改語氣並加入「答錯增加題目」規則，待 Chi 提供新文案後更新
- 可考慮新增「遊戲中心」頁面（各玩家排行比較）

## 已知問題 / 注意事項
- 主檔案：index.html
- GitHub repo：https://github.com/elain-chi/99chill（Public）
- GitHub Pages：https://elain-chi.github.io/99chill
- localStorage：`99chill_list`（玩家清單）、`99chill_p_名字`（玩家資料含 avatar）
- Edit 工具才能安全修改中文內容，不要用 PowerShell echo/cat 寫檔
