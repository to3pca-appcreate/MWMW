MWMW（むうむう）Ver.1.3 PWA 試験運用版

追加
- PWA対応
- ホーム画面用 manifest / アイコン
- Service Workerによる基本オフライン対応
- 手動バックアップ（JSON）
- 手動復元（JSON）
- Ver.1.2の機能を継承

最短の公開手順
1. このZIPを展開
2. 中身すべてをGitHubのMWMW用リポジトリへアップロード
3. GitHub PagesまたはFirebase HostingでHTTPS公開
4. iPhoneのSafariで公開URLを開く
5. Safariの共有 → ホーム画面に追加
6. ホーム画面の「むうむう」から起動
7. 数件登録 → 閉じる → 再起動 → データ保持確認
8. バックアップを書き出して「ファイル」/ iCloud Drive等へ保存
9. 復元テスト

注意
- タスク本体はまだ端末ブラウザのlocalStorage保存です。
- PWA削除やSafariのWebサイトデータ削除等で消える可能性があります。
- 大切なデータはバックアップしてください。
- クラウド自動同期・定期自動バックアップ・通知は未実装です。
