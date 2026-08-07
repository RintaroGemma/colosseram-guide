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
