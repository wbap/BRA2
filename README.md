# BRA Resources
This repository provides release information for BRA (Brain Reference Architecture) Template and related tools.

## Latest Release
**BRA 2.2** (Released: 2025-08-03) [BRAES](https://sites.google.com/wba-initiative.org/braes/) accepts submissions in the following versions:

|Component|Download|
|---------|--------|
|Template-v2-2.bra|[Link (Google Sheets)](https://docs.google.com/spreadsheets/d/1l3pDJaEAmQWwdQi0rcSETjBqeL1Q4AmMtEug90yJ1Fg/edit?usp=drive_link)　Once you open the link, copy it to your Google Drive.|
|BRA Data Review Tool (ver. 4.2) for v2-2|[Link (Google Sheets)](https://docs.google.com/spreadsheets/d/1KWo73IzeepZpJbIF5kUhHFxwuiKXNUkMtx-uOmDy_Xk/edit?usp=drive_link)　Once you open the link, copy it to your Google Drive.|
|BRA data: Error code List (Master)|[Link (Google Sheets)](https://docs.google.com/spreadsheets/d/1mCQOmjBRIx-k12a2x8uV3aSKKZ5dDW0na4bVnZtAzhM/edit?usp=drive_link)|

### Manuals
|Document|Link|
|---------|--------|
|Brain-morphic Software Design Guide ver.2|[jp](https://docs.google.com/document/d/1xGorlRWsAWd52myxHjkLeqmCi99DisWVVQDII1RrqEI/edit?usp=drive_link) / [en](https://docs.google.com/document/d/1X4ckkCky35p_enPim6H39zJLxSPD45Q9R5qMvTxJjbI/edit?usp=drive_link)|
|BRA Data Preparation Manual (v2)|[jp](https://docs.google.com/document/d/1aFM8PA0R082RUbKMyQYvl0AcFtupepMvZYNbAqWrp10/edit?usp=drive_link) / [en](https://docs.google.com/document/d/14zFEfylyXX_IUqHt_UBPbxXRhmG4fYBdlLVe1txWNFE/edit?usp=drive_link)|
|BRA Data Review Manual|[jp](https://docs.google.com/document/d/1JM7z91gm3FQ9s3Tot75w-FnpsG8WULSbuv9O80OWafo/edit?usp=drive_link)|
|BRA Data Review Tool Manual|[jp](https://docs.google.com/document/d/1eN3XNqynR2hRsRxJwWBwNp617GZ2KAOgHSAXtOWVrS8/edit?usp=drive_link) / [en](https://docs.google.com/document/d/1_YtvGkHYt04zG6WmGC4-Ad4oNDbHOZsAOpFsbfmZQn0/edit?usp=drive_link)|

### BRA Data Infrastructure
|Component|Link|
|---------|--------|
|WholeBIF|[Link (Google Sheets)](https://docs.google.com/spreadsheets/d/1Wt7pJKpi_mVKUeyziPuKcXQwB10u8b0T6RCz8gNe9fc/edit?usp=drive_link)|
|WholeBIF-RDB||
|BDBRA||

## Component Relationships
```
Template ◄──1:1──► Review Tool
    │                  │
    │ references       │ references
    ▼                  ▼
WholeBIF          Error Code
    ▲
    │ generated from
WholeBIF-RDB
    ▲
    │ stored in
  BDBRA
```

## Links
Compatibility Matrix

[Release History](RELEASE.md)

Motif Library

## Related Links
[WBAI Official Website](https://wba-initiative.org/)

About BRA-Driven Development

