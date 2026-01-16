# Create a GitHub repo from this zip (concise)

## Option A — GitHub website
1. Unzip `Canopy.zip` on your computer.
2. Go to GitHub → **New repository**.
3. Name it (example): `canopy`.
4. Choose **Private** (recommended for early pilots).
5. Create repository.
6. On your computer, open a terminal in the unzipped `Canopy/` folder.
7. Run:
   - `git init`
   - `git add .`
   - `git commit -m "Initial Canopy bootstrap"`
   - `git branch -M main`
   - `git remote add origin <your-repo-url>`
   - `git push -u origin main`

## Option B — GitHub CLI (if installed)
1. Unzip `Canopy.zip`.
2. In the `Canopy/` folder:
   - `git init`
   - `git add . && git commit -m "Initial Canopy bootstrap"`
   - `gh repo create canopy --private --source=. --remote=origin --push`
