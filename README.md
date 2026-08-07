# コロッセオ日本語音声ガイド — PWA版

## 公開方法（おすすめ：GitHub Pages）
1. GitHubで新しいPublic repositoryを作成
2. このフォルダの4ファイルをアップロード
3. Settings → Pages → Sourceを「Deploy from a branch」
4. Branchを「main」、Folderを「/ (root)」にしてSave
5. 表示された `https://ユーザー名.github.io/リポジトリ名/` をiPhoneのSafariで開く
6. Safariの共有 → ホーム画面に追加

GitHub PagesはHTTPSで配信できます。PWAのService WorkerもHTTPS環境で利用できます。

## 注意
現在の音声はブラウザ標準の日本語音声合成です。高品質な録音ナレーションにする場合は、次の段階でMP3/M4A音声を各スポットに追加し、完全オフライン再生へ変更します。


## v3：原稿表示機能
各スポットを選択すると、その音声ナレーションの全文を画面に表示します。

### GitHub Pagesの更新方法
既存リポジトリで、今回のZIP内のファイルを同名ファイルへ上書きしてください。
特に `index.html` と `sw.js` を更新してください。
GitHub Pages側の設定変更は不要です。
