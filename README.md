# 7つの習慣プレゼンテーション（GitHub Pages対応）

## 公開手順
1. GitHubにログインし、右上の **+ → New repository** を選択します。
2. Repository name を `7-habits-presentation` などに設定します。
3. 公開範囲を **Public** にしてリポジトリを作成します（誰でも閲覧できる公開になります）。
4. **Add file → Upload files** から、このフォルダー内の `index.html` をアップロードして **Commit changes**。
5. リポジトリの **Settings → Pages** を開きます。
6. **Build and deployment** の Source を **Deploy from a branch**、Branch を **main**、フォルダーを **/(root)** にして **Save**。
7. 数分後、同じPages画面に表示される `https://ユーザー名.github.io/7-habits-presentation/` のURLで公開できます。

## ブラウザーで文章を修正
- 公開ページまたは `index.html` をブラウザーで開きます。
- 左下の **文章を編集** を押します。
- 点線で囲まれた文章をクリックして修正します。
- **修正版HTMLを保存** を押すと、編集内容を含むHTMLファイルがダウンロードされます。
- GitHub Pagesにも反映したい場合は、保存したHTMLを `index.html` という名前にして、GitHubリポジトリの既存 `index.html` を置き換えてコミットします。

## 注意
- 「修正版HTMLを保存」はローカルにHTMLをダウンロードします。GitHub上の公開ページを自動で書き換える機能ではありません。公開版の更新には、保存したHTMLをGitHubへ再アップロードしてコミットしてください。
- Publicリポジトリでは資料の内容が誰でも閲覧できます。機密情報を追加しないでください。
- このHTMLは画像を埋め込んだ単一ファイルなので、画像フォルダーは不要です。
