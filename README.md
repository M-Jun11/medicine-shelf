# medicine-shelf（医薬品棚管理）

- 画面：`medicine_shelf_pass.html`（GitHub Pages で公開）。データは Firebase（プロジェクト med-shelf-bc28a）の Firestore（東京）
- ログイン：共有パスワード（Firebase Authentication のメール/パスワードの共有アカウント）。管理者は Google アカウントでも入れる。読み書きできるアカウントは Firestore のルールで決める（ルールはこのリポジトリには置かない）
- パスワードはコードに書かない（このリポジトリは公開）
- **患者の情報（氏名など個人を特定できるもの）は入れない。入れることになったら、ログイン方式・保存のしかたを再検討する**
