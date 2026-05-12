# flex-lecture

HTML / CSS（Tailwind）の演習用リポジトリです。

---

## 事前に必要なもの

以下の3つをあらかじめインストールしておいてください。

| ツール | 用途 | ダウンロード先 |
|---|---|---|
| Git | ファイルをダウンロードするために必要 | https://git-scm.com |
| VS Code | コードを編集するエディタ | https://code.visualstudio.com |
| Live Server（VS Code拡張機能） | ブラウザでリアルタイムに確認するために必要 | VS Code 内で検索してインストール |

### Live Server のインストール方法

1. VS Code を開く
2. 左のアイコンバーから「拡張機能」（四角のアイコン）をクリック
3. 検索欄に `Live Server` と入力
4. **Live Server**（作者: Ritwick Dey）をインストール

---

## リポジトリのフォーク

フォークとは「このリポジトリを自分の GitHub アカウントにコピーする」操作です。  
フォークすることで、自分のコピーを自由に編集できるようになります。

1. このページ上部右の **「Fork」** ボタンをクリック
2. **「Create fork」** をクリック
3. 自分のアカウントにリポジトリがコピーされる

---

## HTTPS でクローンする

クローンとは「GitHub 上のリポジトリを自分のパソコンにダウンロードする」操作です。

### 1. フォーク先のリポジトリ URL をコピーする

1. フォークした自分のリポジトリページを開く（URL が `https://github.com/自分のユーザー名/flex-lecture` になっていることを確認）
2. 緑色の **「Code」** ボタンをクリック
3. **「HTTPS」** タブが選択されていることを確認
4. 表示された URL をコピー（例: `https://github.com/yourname/flex-lecture.git`）

### 2. VS Code のターミナルを開く

1. VS Code を起動する
2. 上部メニューの **「ターミナル」→「新しいターミナル」** をクリック
   - ショートカット: Mac は `` Ctrl + ` ``、Windows は `` Ctrl + ` ``
3. 画面下部にターミナルが表示される

### 3. クローンを実行する

ターミナルに以下のコマンドを入力し、Enter を押す。  
`URL` の部分には、さきほどコピーした URL を貼り付けてください。

```bash
git clone URL
```

**実行例：**
```bash
git clone https://github.com/yourname/flex-lecture.git
```

### 4. フォルダを VS Code で開く

```bash
cd flex-lecture
code .
```

---

## Live Server で確認する

1. VS Code のファイル一覧から `index.html` を右クリック
2. **「Open with Live Server」** をクリック
3. ブラウザが自動で開き、演習ページが表示される

---

## ファイル構成

```
flex-lecture/
├── index.html        ← ホーム画面
├── color.html        ← 色を変える
├── flex.html         ← 横並びにする
├── spacing.html      ← 余白を調整する
├── fontsize.html     ← 文字サイズを変える
├── custom.html       ← 自分なりのページを作成してみる
└── custom.css        ← 自由に書けるCSSファイル
```
