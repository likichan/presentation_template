# Presentation Template for Marp (ゼミ発表用)

## フォルダ構成

- themes/ : カスタムテーマやセクション画像
- images/ : ロゴ・挿絵画像（必要に応じて追加）
- template.md : 毎回コピーして発表資料を作る Marp テンプレ
- README.md : このファイル

## 使い方

1. `template.md` をコピーして新しい発表資料を作る
2. タイトルや内容を編集
3. 画像は `images/` フォルダに入れて参照
4. Marp で PDF/HTML などに変換
5. marp "presentations/2025-05-30 前期中間取組発表.md" --pdf --theme ./themes/custom-theme.css
6. ./makepdf.sh "presentations/ファイル名.md"

## 注意事項（抜粋）

- 色：青・黒・白ベース、赤 NG
- 本文 24pt 以上、見出し 32pt 以上、タイトル 48pt 以上推奨
- 余白を十分とる
- 参考文献・出典必須（画像等含む）
- 図表・グラフを積極的に使う
- スライドは 10 行以内を目安

