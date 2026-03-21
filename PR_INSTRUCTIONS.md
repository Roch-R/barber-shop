# How to Create the Pull Request

## Automated (preferred)
1. Terminal: `gh auth login` (browser login)
2. Then: `gh pr create --title \"BlackboxAI Task Updates\" --body \"Changes in blackboxai/update branch:\\n- auth.html ban redirect fix\\n- public-index.html landing refactor\\n- TODO.md PR tracking\" --base main --head blackboxai/update`

## Manual
1. Open https://github.com/Roch-R/barber-shop/compare/main...blackboxai/update?expand=1
2. Click **Create pull request**
3. Title: `BlackboxAI Task Updates`
4. Body:
```
Recent changes:
- f598621: auth.html ban redirect pathname fix; public-index.html simplify landing
- f6ad645, 200fe1b: TODO.md PR progress tracking
```
5. **Create pull request**

Branch ready, changes pushed. Merge to deploy to GitHub Pages.
