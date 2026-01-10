# Release History

## BRA 2.3 （2026-XX-XX）

### BRA Template
#### Resource
- [Template-v2-3.bra (Google Sheets)](https://docs.google.com/spreadsheets/d/1JL20faP7RVK1yTknnHVEXuJsT3eqL3mz-8oI3YiLYZY/edit?usp=drive_link)
  - Attached container-bound scripts: メニューから 拡張機能 > Apps Script で表示
    - Hosting scripts source code on [GitHub Repository](https://github.com/yoshi-ono/BRA-Template-AppsScript)

#### Main changes
- Menu Function
  - "FRG Checker (LLM)" 機能を追加
- FRGシート
  - Capability&Mechanism列へのCoding scheme情報記述の仕様追加
- WholeBIF
  - WholeBIF-RDBから出力される新しいWholeBIFファイルをインポート（データ量が大幅増）
- Connectionsシート
  - 新しいWholeBIFに合わせた列名変更
    - Method score → Method score (PDER) 
    - Journal score → Citation sentiment index

### BRA Data Review Tool
#### Resource
- [BRA Data Review Tool (ver. 4.X) for v2-3 (Google Sheets)]
  - Attached container-bound scripts: メニューから 拡張機能 > Apps Script で表示
    - Hosting scripts source code on [GitHub Repository](https://github.com/yoshi-ono/BRA-Data-Review-Processing)

- ライブラリ参照するスタンドアロン スクリプト: [BRA_Data_Review_Report ver.4 (Google Apps Script)](https://script.google.com/d/1HCJnwNH0_O9blisoo7s3LWs6X3a90C4yd_7K1KJJjQr96tCr-R3Th5BT/edit?usp=drive_link)
  - デプロイ バージョン X
  - Hosting scripts source code on [GitHub Repository](https://github.com/yoshi-ono/BRA-Data-Review-Report)

#### Main changes
- エラーコードリストの更新による自動審査の追加

### BRA data: Error code List
#### Resource
- [BRA data: Error code List (Master) (Google Sheets)](https://docs.google.com/spreadsheets/d/1mCQOmjBRIx-k12a2x8uV3aSKKZ5dDW0na4bVnZtAzhM/edit?usp=drive_link)
#### Main changes
- 自動審査エラーコードの追加
  - Circuits
    - ErrorCode: 105
  - FRG
    - ErrorCode: 448, 449