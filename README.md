# 開発ポートフォリオ

AI・ソフトウェアエンジニアを志望しています。大学の授業・工房、インターンシップ、AIを使った研究開発をまとめています。

| プロジェクト | 取り組んでいること | 主な技術 | 制作体制・主な担当 |
| --- | --- | --- | --- |
| [ロボットサッカー](https://github.com/osuketakino327/autonomous-robot-soccer) | カメラ画像の色・マーカー検出によってロボットやボールの位置を取得し、ゴールにボールを入れるようにロボットが動くためのプログラム。 | Python、OpenCV、NumPy、UDP | 教授から提供されたひな型をもとに、コードを編集して制作 |
| [Space Wars](https://github.com/osuketakino327/shooting-game) | 画面状態の切り替え、敵の出現データ、当たり判定を組み合わせたシューティングゲーム | Java、Swing／AWT | 4人で開発。主に爆発エフェクトと画面全体のデザインを担当 |
| [社内情報機器管理Webシステム](https://github.com/osuketakino327/equipment-management-system) | Excelの申請書を読み取り、その内容を各管理台帳へ反映するWebシステム。10日間のインターンシップで作成した成果物。 | React、Django REST Framework、openpyxl | 2人で開発。主にバックエンドを担当 |
| [テニスフォーム解析・改善アドバイス](https://github.com/osuketakino327/tennis-advice-system) | 単眼動画から20種類の特徴量を計測し、根拠と評価保留を保存する研究用CLI。未知動画の指導評価は開発中 | Python、MediaPipe、NumPy、SciPy、Qwen | 実装範囲：特徴量処理、品質検査、制約付き文章選択、レポート出力 |
| [テニスフォーム動画生成](https://github.com/osuketakino327/tennis-motion-transfer) | 人物写真と動作動画を用いるWan Animate 2の推論。生成品質は検証中 | Python、PyTorch、Diffusers、Accelerate、FFmpeg | 実装範囲：前処理、8 GPU配置、Attention・RoPE・KVキャッシュのメモリ対策、数値検査 |

画像認識とロボット制御、Webアプリケーション、Javaの画面描画に加え、姿勢解析と動画生成の処理系に取り組んでいます。各READMEでは、コードで確認できる機能と、動作確認が済んでいない部分を分けて記載しています。

