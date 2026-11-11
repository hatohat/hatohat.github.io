# hatohat.github.io

ぐみろぐ（https://hatohat.github.io/gumilog/）の Googleログインを動かすためのファイルを置いています。

- `__/auth/` … Firebase Authentication のログイン受け取り役（gumilog-app.firebaseapp.com/__/auth/ から写したもの）。
  ぐみろぐと同じドメインに置くことで、iPhone のホーム画面アプリでもリダイレクトでログインできるようにしています。
- `__/firebase/init.json` … Firebase の公開設定（ページに埋め込む前提の値です）。

Firebase 側が更新されたら、`__/auth/handler.js` などを取り直します。
