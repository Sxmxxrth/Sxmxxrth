# 🚀 GitHub Profile Deployment Guide (`Sxmxxrth/Sxmxxrth`)

This repository contains the special profile repository configuration for **Samarth Sugandhi** (`Sxmxxrth`). When pushed to `https://github.com/Sxmxxrth/Sxmxxrth`, its `README.md` will automatically render on your primary GitHub user profile.

---

## 🛠️ Step-by-Step Deployment Instructions

### Step 1: Ensure the Special Repository Exists on GitHub
1. Navigate to [GitHub New Repository](https://github.com/new).
2. Enter the Repository name: **`Sxmxxrth`** (must match your GitHub username exactly).
3. Set the visibility to **Public** (required for profile README display).
4. Do NOT initialize with a README, .gitignore, or license (we have provided these already).
5. Click **Create repository**.

---

### Step 2: Push Local Profile Repository to GitHub
Run the following commands inside this directory (`/Users/samarth/.gemini/antigravity/scratch/Sxmxxrth_profile`):

```bash
cd /Users/samarth/.gemini/antigravity/scratch/Sxmxxrth_profile
git init
git add .
git commit -m "feat: launch elite maximalist AI/ML engineer profile suite"
git branch -M main
git remote add origin https://github.com/Sxmxxrth/Sxmxxrth.git
git push -u origin main
```

*(Note: If you have already initialized `Sxmxxrth` on GitHub, run `git pull --rebase origin main` before `git push`.)*

---

### Step 3: Configure GitHub Actions Permissions for Snake Animation
To allow the automated snake contribution generator to commit to the `output` branch:
1. In your `Sxmxxrth/Sxmxxrth` repository, click **Settings** (top navigation).
2. On the left sidebar, click **Actions** > **General**.
3. Scroll down to **Workflow permissions**.
4. Select **Read and write permissions**.
5. Check the box for **Allow GitHub Actions to create and approve pull requests**.
6. Click **Save**.

---

### Step 4: Run the Snake Generator for the First Time
1. Click the **Actions** tab in your repository.
2. Under "Workflows" on the left, click **Generate Contribution Snake Animation**.
3. Click the **Run workflow** dropdown button on the right, select `Branch: main`, and click **Run workflow**.
4. Within 30 seconds, the workflow will complete and create the `output` branch containing:
   - `github-contribution-grid-snake.svg`
   - `github-contribution-grid-snake-dark.svg`
5. Refresh `https://github.com/Sxmxxrth` — your animated contribution snake will now be live on your profile!

---

### 🌟 What's Included in Your Suite

- **Dynamic Typing Banner**: Rotating titles via `readme-typing-svg`.
- **Identity & Verification Badges**: LinkedIn, Verified Email, Degree, Location, Immediate Joiner.
- **Architectural Projects Matrix**: Fine-Tuned Mistral-7B, Production Mutual Fund RAG (0.81 RAGAS), ML Drift Monitor (PSI + SHAP), and Cold Outreach Engine (>1,745+ dispatches).
- **Categorized Tech Stack Badges**: Languages, Deep Learning/ML, GenAI/LLMOps, Vector DBs, Cloud/Backend.
- **Stats & Metrics Cards**: Dark Radical Theme synced with `#00ffcc` accents.
- **Automated Daily Snake Animation**: Automated GitHub Actions CI/CD pipeline.
