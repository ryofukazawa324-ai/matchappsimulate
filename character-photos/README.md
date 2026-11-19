# Match Lab character photos

プロフィール画像を追加するフォルダです。

## 追加手順
1. この character-photos フォルダへ PNG / JPG / WebP 画像をアップロードします。
2. ファイル名は profile-1-sakura.png のように、対象が分かる半角英数字を推奨します。
3. photo-map.json にプロフィールID・人物名・画像ファイル名を追記します。
4. サイトに反映するには、app.js の photoFiles に同じパスを登録します。

## 現在の割り当て
割り当て一覧は photo-map.json を参照してください。

## 注意
- GitHub Pages の相対パスで読み込むため、画像ファイルをこのフォルダから移動しないでください。
- 新しい人物用の写真は、既存画像を上書きせず別ファイル名で追加してください。
- 画像を入れ替える場合は、対象プロフィールIDを確認してから photo-map.json と app.js の両方を更新してください。
