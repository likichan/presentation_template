# Presentation Template for Marp

## フォルダ構成

- themes/ : カスタムテーマやセクション画像
  - template.md : 毎回コピーして発表資料を作る Marp テンプレ
- images/ : ロゴ・挿絵画像（必要に応じて追加）
- README.md : このファイル

## 使い方

1. `template.md` をコピーして新しい発表資料を作る
2. タイトルや内容を編集
3. 画像は `images/` フォルダに入れて参照
  - 画像の挿入などは参考文献の記事を見てください！
4. Marp で PDF/HTML などに変換
  - marp "presentations/2025-05-30 前期中間取組発表.md" --pdf --theme ./themes/custom-theme.css
5. プレビューを確認したい時は4を実行した上で下のコマンドを実行
  - ./makepdf.sh "presentations/ファイル名.md"
  - marp ファイル.md --server --allow-local-files

# スライドのデザインについて
- スライドの見た目を自分好みにカスタマイズしたいという人は`themes/custom.css`をいじってみてください！下に参考文献置いておきます！

# イラストなど
- https://undraw.co/

# 参考文献
- https://qiita.com/tomo_makes/items/aafae4021986553ae1d8#tldr

