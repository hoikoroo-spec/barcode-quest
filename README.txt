バーコードクエスト 試作版 v0.1

【iPhoneへの公開】
1. GitHubで新しいPublicリポジトリ barcode-quest を作成。
2. このフォルダ内の5ファイル（index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png）をリポジトリ直下にアップロード。
3. Settings → Pages → Build and deployment → Deploy from a branch → main / (root) → Save。
4. 数分後に https://hoikoroo-spec.github.io/barcode-quest/ をSafariで開く。
5. 共有 → ホーム画面に追加。

【機能】
- モンスター召喚（24種類の基本モンスター、同じバーコードは同じ個体）
- ダンジョン生成（4地形・難易度5段階・自由探索）
- 3体パーティー、ターン制バトル、経験値・分岐進化・秘石
- ★5ダンジョンの初回ボス討伐で地形限定モンスター
- 自動セーブ、JSON書き出し/読み込み、PWA

【試作版の制約】
- カメラ自動認識はブラウザのBarcodeDetector対応時のみ。非対応時は数字手入力。
- モンスター画像は仮の絵文字。高画質イラスト・ドット絵は今後差し替え。
- 戦闘・育成バランスは仮設定。モンスターは24種類の基本種を用意。
- セーブは端末のブラウザに保存。バックアップ書き出し推奨。
- バーコードのチェックデジットを検証するため、適当な数字は使えない場合あり。
