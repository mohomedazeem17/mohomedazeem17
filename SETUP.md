# ⚡ MOHOMED AZEEM — GitHub Profile Setup Guide

## STEP 1 — Create the special profile repo
1. Go to github.com/new
2. Repo name: `mohomedazeem17` (EXACTLY your username, case-sensitive)
3. ✅ Public  ✅ Add README  → Create Repository

## STEP 2 — Upload files
Replace the default README.md with the `README.md` from this folder.
Upload the `assets/` folder (cube.svg, pipeline.svg).
Upload the `.github/workflows/` folder with both workflow files.

Final structure should look like:
```
mohomedazeem17/
├── README.md
├── assets/
│   ├── cube.svg
│   └── pipeline.svg
└── .github/
    └── workflows/
        ├── 3d-contrib.yml
        └── snake.yml
```

## STEP 3 — Enable workflow permissions
Go to: Repo → Settings → Actions → General
→ Set "Workflow permissions" = ✅ Read and write permissions
→ Save

## STEP 4 — Run Snake workflow
Go to Actions tab → "Generate Contribution Snake" → "Run workflow" → Run
Wait 60 seconds. Check if an `output` branch was created. ✅

## STEP 5 — Run 3D Graph workflow
Go to Actions tab → "3D Contribution Graph" → "Run workflow" → Run
Wait 2-3 minutes. Check if `profile-3d-contrib/` folder appears in the main branch. ✅

## STEP 6 — Verify everything renders
Open your GitHub profile → Check all sections load correctly.

---

## THINGS TO PERSONALIZE FURTHER

- [ ] Add your Portfolio link (badge currently points to `#` — update once you have one)
- [ ] Add LinkedIn badge if/when you create a profile
- [ ] Swap `f1-performance-dashboard` link once that repo is public
- [ ] Add real repo links for any project once pushed to GitHub
- [ ] Pin your top 6 repos: github.com/mohomedazeem17 → "Customize your pins"
- [ ] Optional: WakaTime (wakatime.com) to track real coding hours
- [ ] Optional: add more public repos to strengthen the stats cards

## WHY THIS VERSION IS DIFFERENT

| Feature | Generic Template | Your Profile |
|---------|-------------------|----------------|
| Theme | Blue DevOps | Green/cyan cybersecurity terminal |
| Identity block | Bullet list | Real YAML operator config |
| Pipeline diagram | CI/CD stages | Recon → Scan → Analyze → Secure |
| Stats | Just one card | 3-card (stats + langs + streak) |
| Contribution viz | Nothing | SNAKE + 3D isometric graph |
| Projects | Badge spam | `ps aux`-style process table |
| Sprint tracker | Nothing | Log-style progress bars |
| Data | Fake/generic | Your real CV background + projects |
