# コントリビュートガイド（貢献ガイド）

このプロジェクトへの貢献（練習）手順です。

1. **Fork（フォーク）**
   このリポジトリを自分のアカウントにFork（複製）します。

2. **Clone（クローン）**
   Forkしたリポジトリをローカル（自分のPC）にClone（ダウンロード）します。
   ```bash
   git clone https://github.com/YOUR_USERNAME/git-mukashibanashi.git
   ```

3. **Branch（ブランチ）**
   新しいブランチ（作業用の枝分かれ）を作成して作業します。
   ```bash
   git checkout -b fix/momotaro-typo
   ```

4. **Change（チェンジ/変更）**
   ファイルを編集します。

5. **Commit（コミット）**
   変更を保存（コミット）します。
   ```bash
   git add .
   git commit -m "桃太郎の誤字を修正"
   ```

6. **Push（プッシュ）**
   自分のリモートリポジトリ（GitHub上）にPush（送信）します。
   ```bash
   git push origin fix/momotaro-typo
   ```

7. **Pull Request（プルリクエスト）**
   GitHub上でPull Request（変更の統合依頼）を作成します。
