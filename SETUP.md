# Setup — Halloween GitHub Profile

## 1. Create the profile repository
Create a **public** repository named exactly `Jasveer399` (same spelling/capitalization as your GitHub username).

## 2. Add these files
Copy `README.md`, the `assets/` folder, and `.github/workflows/snake.yml` into the root of that repository.

Expected layout:

```text
Jasveer399/
├── README.md
├── assets/
│   ├── halloween-banner.png
│   └── halloween-avatar.png
└── .github/
    └── workflows/
        └── snake.yml
```

## 3. Enable the contribution snake
In the repository, open **Settings → Actions → General** and make sure workflows have permission to write to the repository. Commit the workflow and run it once from **Actions → Generate contribution snake → Run workflow**. It publishes the generated SVG to the `output` branch.

## 4. Set your GitHub avatar
Open **GitHub → Settings → Public profile → Edit** and upload `assets/halloween-avatar.png`.
The avatar file is a suggested Halloween-themed illustration, not a photograph or likeness.

## 5. Optional banner
GitHub does not provide a native profile-header banner field. The banner is displayed at the top of the README instead.

## 6. Check project links
The README uses the visible pinned names `echo-ai`, `podcaster`, `stack`, and `portfolio`, plus the Darzi project. If any repository slug differs, update its URL in the project table.

## Notes
- GitHub README rendering supports a subset of HTML; custom CSS and JavaScript are not supported.
- GitHub stats and streak cards are provided by third-party services, so they may occasionally be unavailable.
- Contribution totals and language percentages are deliberately dynamic; no hard-coded stats are used.
