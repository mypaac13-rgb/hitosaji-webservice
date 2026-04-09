# LINE公式アカウント 開設メモ

このサイトの問い合わせ導線は、現在 [index.html](/Users/aya/claude/30_shop/webservice/index.html) で LINE公式アカウント向けに変更済みです。

## 1. 公式アカウントを作成

公式の開設ページ:

- https://entry.line.biz/start/jp/

管理画面:

- https://manager.line.biz/

LINEアカウント、またはビジネス用メールアドレスで作成できます。

## 2. 最低限やる設定

- アカウント名を設定
- プロフィール画像を設定
- あいさつメッセージを設定
- 応答モードを「チャット」にして、手動で返信できる状態にする

## 3. サイトへ反映する場所

[index.html](/Users/aya/claude/30_shop/webservice/index.html) のこのURLを差し替えてください。

```html
href="https://lin.ee/REPLACE_WITH_YOUR_OFFICIAL_LINE"
```

LINE公式アカウントの「友だち追加URL」や `lin.ee` の短縮URLが取得できたら、そのURLに置き換えれば完了です。

## 4. 補足

個人LINEではなく、LINE公式アカウントを使う方が次の点で適しています。

- お店用と個人用を分けられる
- あいさつメッセージを設定できる
- 営業時間やプロフィールを見せられる
- 今後クーポンやリッチメニューも追加できる
