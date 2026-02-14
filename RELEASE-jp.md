# Release History

## BRA 2.2 （2025-08-03）

### BRA Template
#### Resource
- [Template-v2-2.bra (Google Sheets)](https://docs.google.com/spreadsheets/d/1l3pDJaEAmQWwdQi0rcSETjBqeL1Q4AmMtEug90yJ1Fg/edit?usp=drive_link)
  - Attached container-bound scripts: メニューから 拡張機能 > Apps Script で表示
    - Hosting scripts source code on [GitHub Repository](https://github.com/yoshi-ono/BRA-Template-AppsScript)

#### Main changes
- Menu Function
  - "GraphGenerator" 機能を強化
    - Mermaidコード出力 → CSVコード出力
- FRG シート
  - 自動計算項目の更新
    - Region Category, Interface, Capability
  - 入力項目
    - 追加: Capability&Mechanism
    - 削除: Mechanism
  - LLM チェック項目の追加、削除（将来の機能）

### BRA Data Review Tool
#### Resource
- [BRA Data Review Tool (ver. 4.2) for v2-2 (Google Sheets)](https://docs.google.com/spreadsheets/d/1KWo73IzeepZpJbIF5kUhHFxwuiKXNUkMtx-uOmDy_Xk/edit?usp=drive_link)
  - Attached container-bound scripts: メニューから 拡張機能 > Apps Script で表示
    - Hosting scripts source code on [GitHub Repository](https://github.com/yoshi-ono/BRA-Data-Review-Processing)

- ライブラリ参照するスタンドアロン スクリプト: [BRA_Data_Review_Report ver.4 (Google Apps Script)](https://script.google.com/d/1HCJnwNH0_O9blisoo7s3LWs6X3a90C4yd_7K1KJJjQr96tCr-R3Th5BT/edit?usp=drive_link)
  - デプロイ バージョン 2
  - Hosting scripts source code on [GitHub Repository](https://github.com/yoshi-ono/BRA-Data-Review-Report)

#### Main changes
- エラーコードリストの更新による自動審査の追加

### BRA data: Error code List
#### Resource
- [BRA data: Error code List (Master) (Google Sheets)](https://docs.google.com/spreadsheets/d/1mCQOmjBRIx-k12a2x8uV3aSKKZ5dDW0na4bVnZtAzhM/edit?usp=drive_link)
#### Main changes
- 自動審査エラーコードの追加
  - FRG
    - ErrorCode: 433, 450, 451, 452, 573, 574, 575
