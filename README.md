# am-i-human
ラムダ技術部のやつのCloudflare Turnstileバージョンです。
呼び出し回数制限なしだ、ありがたい。
## 環境変数
`.env.js`に
```js
globalThis.key = "[Cloudflare Turnstileのサイトキー]"
```
を記入してください。
`windows.key =`や`var key =`でもいいかもしれませんが`globalThis =`のみ動作確認しています。
