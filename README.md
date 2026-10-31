# tw-tax-planner-data

「台灣稅務專家」App 的法規參數與實務見解資料，透過 GitHub Pages 提供給 App 檢查更新。

- `rules.json`：遺產稅、贈與稅、綜所稅、最低稅負、房地合一等參數（含版本與法源）
- `practice-notes.json`：法條、財政部函釋、憲法法庭判決的實務見解摘要

App 只會在 `version` 比手上的版本新時才套用。內容由主專案的 `scripts/publish-data.sh` 產生並發佈，請勿直接手動修改。

本資料僅供參考，不構成法律或稅務意見。
