Hinowa Infinity — 外部辞書読込デモ (Step 4)

使い方:
1) フォルダ構成のまま Web に配置（GitHub Pages / Netlify / ローカルHTTPサーバ推奨）
   /
   ├─ index.html
   └─ data/
       ├─ emotion_keywords.json
       ├─ summary_templates.json
       └─ mode_config.json

2) ブラウザで index.html を開く → 「外部JSONを読み込む」ボタン。
   * file:// で直接開くと fetch がブロックされる場合があります。
     → GitHub Pages 等の公開URLで開くか、画面の「手動読込」からJSONを選択してください。

3) 「デモ入力」→「計算」でFASと要約を確認。

メモ:
- JSONを差し替えるだけで、語彙や要約テンプレ、しきい値が即反映されます。
- 端末差異: iPhone/Safari は公開URL推奨。Android/Chrome もOK（手動読込対応）。
