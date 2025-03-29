# How To Communicate with Designer

## Requirements

### User Scenario

- 使用者需要一個可以快速、簡單的方式，向設計師表達需求，並獲得設計師的回饋。
- 建立一個工具網站，讓使用者可以根據需求去選擇想要的版型，並依版型內的區塊提示，提供需要的對應資料。
  - [參考資料](https://docs.google.com/presentation/d/1Kc39MRu0zTwyE0K6LLO7B8KMdPf-konx_-PL0SN75tE/edit?slide=id.g33e1fcaf5bf_0_133#slide=id.g33e1fcaf5bf_0_133)

### technical requirements

- 可以使用快速成型的 JS 框架，例如 React、Vue、Angular 等等。
- 可以使用 CSS 框架，例如 Bootstrap、Tailwind 等等。
- 可以使用免費託管服務，例如 GitHub Pages、Netlify 等等。
- 無資料保存需求。

### functional requirements

- 使用者可以選擇想要的版型。
- 使用者可以根據版型內的區塊提示，提供需要的對應資料。
- 使用者可以將填完資料的版型畫面，匯出成 HTML 格式（檔案）。

## Analysis

### Analysis of functional requirements

- 使用者可以選擇想要的版型。
  - 使用者可以在首頁透過選單，選擇想要的版型。
- 使用者可以根據版型內的區塊提示，提供需要的對應資料。
  - 使用者可以在選擇版型後，進入填寫資料的頁面，並根據版型內的區塊提示，提供需要的對應資料。
- 使用者可以將填完資料的版型畫面，匯出成 HTML 格式（檔案）。
  - 使用者可以在填寫資料的頁面，點擊匯出按鈕，將填完資料的版型畫面，匯出成 HTML 格式（檔案）。

### Analysis of technical requirements

- 可以使用快速成型的 JS 框架，例如 React、Vue、Angular 等等。
  - 使用 Vue3 框架，因為 Vue3 是一個快速成型的 JS 框架，並且有很多現成的套件可以使用。
- 可以使用 CSS 框架，例如 Bootstrap、Tailwind 等等。
  - 使用 Bootstrap 框架，因為 Bootstrap 是一個快速成型的 CSS 框架，並且有很多現成的套件可以使用。
- 可以使用免費託管服務，例如 GitHub Pages、Netlify 等等。
  - 使用 GitHub Pages，因為 GitHub Pages 是一個免費的靜態網站託管服務，並且可以直接從 GitHub 上部署。
- 無資料保存需求。
  - 因為這個網站不需要保存資料，所以不需要使用資料庫。
