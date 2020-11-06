```
yarn create nuxt-app demo
cd demo
yarn dev
```
see : `http://localhost:3000`


**チェックしておく**
- Routing
- UI Framework
- TypeScript

## Nuxt.jsとはそもそも
- Vue用のSSR対応ライブラリ
[Nuxt\.jsで変わる開発フローとUniversal JavaScriptのイマ \#jsfes \- Speaker Deck](https://speakerdeck.com/potato4d/nuxt-dot-jsdebian-warukai-fa-hurotouniversal-javascriptfalseima-number-jsfes?slide=19)

## Nuxt.jsが提供する機能
ref: [【v2対応】Nuxt\.jsとFirebaseを組み合わせて爆速でWebアプリケーションを構築する \- Qiita](https://qiita.com/potato4d/items/cfddeb8732fec63cb29c)

- Vueファイルで記述できること
- コードを自動的に分割すること
- サーバーサイドレンダリング
- 非同期データをハンドリングするパワフルなルーティング
- 静的ファイルの配信
- ES6/ES7のトランスパイレーション
- JSとCSSのバンドル及びミニファイ
- Head要素の管理
- 開発モードにおけるホットリローディング
- SASS, LESS, Stylus などのプリプロセッサのサポート
- HTTP/2 push headers ready
- モジュール構造で拡張できること


## Nuxt.jsとFirebaseを組み合わせてできること

- ルーティングを自分で作成する必要がなく
- Vuexのストアはオートローディングされ
- SSRはデフォルトで対応、自由に付け外しができる
