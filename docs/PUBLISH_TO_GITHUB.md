# Quickstart: publish this repo to GitHub

## Option A — GitHub Desktop (recommended for beginners)
1. Install GitHub Desktop
2. File → Add Local Repository… → select this folder
3. Publish repository → Public

## Option B — Command line
```bash
cd path/to/this/folder
git init
git add .
git commit -m "Add Power BI dashboard project"
git branch -M main
git remote add origin https://github.com/<YOUR_USER>/<REPO_NAME>.git
git push -u origin main
```

## After publishing
- Add screenshots to `docs/images/`
- Edit README: add your story + KPIs + insights
- Pin the repo in your GitHub profile
