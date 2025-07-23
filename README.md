# Soweto Luxe Interiors

## Development and Deployment Workflow

- **main** branch: Live production site.
- **dev** branch: Development and testing branch.
- Separate **staging repo** (`soweto-luxe-interiors-staging`) for safe testing with GitHub Pages enabled on `dev` branch.

---

## How to Use

1. Work on the `dev` branch locally.
2. Commit and push changes to **both**:
   - `origin/dev` (main repo dev branch)
   - `staging/dev` (staging repo dev branch)
3. Test your changes live on the staging site:  
   https://sibu-dubazane.github.io/soweto-luxe-interiors-staging/
4. After thorough testing and verification, merge `dev` into `main` branch to deploy changes to the live site.

---

## Staging Repository Details

- The staging repo is a **clone of the dev branch** specifically for testing and previewing changes safely.
- GitHub Pages is enabled on the `dev` branch of the staging repo to provide a live preview link.
- This separation prevents any accidental changes affecting the live site.
- Use the staging site to:
  - Test new layouts, features, and fixes.
  - Share progress with team members or clients safely.
  - Verify changes work as expected before going live.

---

## Important Notes

- **Do NOT commit directly to `main`**. Always use `dev` and PRs to control what goes live.
- Keep both `origin` and `staging` remotes updated with your latest dev work.
- Use pull requests for merging `dev` into `main` to allow reviews and avoid errors.
- If you break something, it will be caught in staging, NOT on the live site.

---

_Last updated: 2025-07-23_
