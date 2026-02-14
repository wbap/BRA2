# Release History

## BRA 2.2 (2025-08-03)

### BRA Template
#### Resource
- [Template-v2-2.bra (Google Sheets)](https://docs.google.com/spreadsheets/d/1l3pDJaEAmQWwdQi0rcSETjBqeL1Q4AmMtEug90yJ1Fg/edit?usp=drive_link)
  - Attached container-bound scripts: View from menu Extensions > Apps Script
    - Hosting scripts source code on [GitHub Repository](https://github.com/yoshi-ono/BRA-Template-AppsScript)

#### Main changes
- Menu Function
  - Enhanced "GraphGenerator" feature
    - Mermaid code output → CSV code output
- FRG Sheet
  - Updated automatic calculation fields
    - Region Category, Interface, Capability
  - Input fields
    - Added: Capability&Mechanism
    - Removed: Mechanism
  - LLM check items added/removed (future feature)

### BRA Data Review Tool
#### Resource
- [BRA Data Review Tool (ver. 4.2) for v2-2 (Google Sheets)](https://docs.google.com/spreadsheets/d/1KWo73IzeepZpJbIF5kUhHFxwuiKXNUkMtx-uOmDy_Xk/edit?usp=drive_link)
  - Attached container-bound scripts: View from menu Extensions > Apps Script
    - Hosting scripts source code on [GitHub Repository](https://github.com/yoshi-ono/BRA-Data-Review-Processing)

- Standalone script referencing library: [BRA_Data_Review_Report ver.4 (Google Apps Script)](https://script.google.com/d/1HCJnwNH0_O9blisoo7s3LWs6X3a90C4yd_7K1KJJjQr96tCr-R3Th5BT/edit?usp=drive_link)
  - Deployed version 2
  - Hosting scripts source code on [GitHub Repository](https://github.com/yoshi-ono/BRA-Data-Review-Report)

#### Main changes
- Added automatic review based on error code list updates

### BRA data: Error code List
#### Resource
- [BRA data: Error code List (Master) (Google Sheets)](https://docs.google.com/spreadsheets/d/1mCQOmjBRIx-k12a2x8uV3aSKKZ5dDW0na4bVnZtAzhM/edit?usp=drive_link)
#### Main changes
- Added automatic review error codes
  - FRG
    - ErrorCode: 433, 450, 451, 452, 573, 574, 575
