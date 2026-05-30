# GitHub Profile Setup

## 1. Create the special profile repository

Create a **public** repository named exactly:

`Usama-Afzal-SQA`

GitHub shows the `README.md` from that repository on your profile page.

## 2. Copy these files into that repository

Copy everything from this folder:

- `README.md`
- `assets/usama-afzal-sqa-banner.svg`
- `.github/workflows/snake.yml`

## 3. Push to your default branch

Push the files to `main`.

If you use a different default branch, update `.github/workflows/snake.yml` so the `push` trigger matches your branch name.

## 4. Enable the snake workflow

If the snake workflow does not push files to the `output` branch:

- Open your repository on GitHub
- Go to `Settings > Actions > General`
- Set `Workflow permissions` to `Read and write permissions`
- Run the `Generate contribution snake` workflow once from the `Actions` tab

The contribution animation will appear after the workflow creates the `output` branch.

## 5. Update your GitHub profile settings

Suggested profile settings:

- **Name:** `Usama Afzal`
- **Bio:** `SQA Engineer at Goally | Automation, Firmware QA, Mobile Testing, and AI-Assisted Debugging`
- **Company:** `@Goally`
- **Website:** `https://linktr.ee/Usama_Afzal_SQA`
- **Location:** `Lahore, Pakistan`

## 6. Pin the right repositories

Suggested pinned repositories:

- `StandUpBot`
- `HybridApp_Automation_Appium`
- `Checkout_Automation_Cypress`
- `AndroidApp_Automation`

If you publish a stronger API-testing, Postman, or QA-framework repo later, replace `AndroidApp_Automation` first.

## 7. Optional cleanup before publishing

- Remove the email badge from `README.md` if you do not want your Gmail address shown publicly
- Improve the descriptions of your public repositories so the profile cards and repository list look sharper
- Add screenshots or short README files to your best projects, especially the Appium and Cypress repos
