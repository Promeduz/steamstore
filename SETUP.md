# Setup Instructions for GitHub

## Initial Setup

1. **Create the repository on GitHub:**
   - Go to https://github.com/new
   - Repository name: `steamstore`
   - Description: "Public repository for Steam store page image assets for multiple games"
   - Set to **Public**
   - Do NOT initialize with README, .gitignore, or license (we already have these)

2. **Connect and push to GitHub:**

```bash
cd C:\Code\steamstore
git add .
git commit -m "Initial commit: Add support badge images for Flipworld"
git branch -M main
git remote add origin https://github.com/Promeduz/steamstore.git
git push -u origin main
```

**Note:** Repository is already set up and pushed to GitHub.

## Using the Images

Once pushed, you can use the raw GitHub URLs. It is recommended to use the **256px** versions for both consistency and quality, as Steam will scale them down as needed.

### Flipworld URLs

- **Support Badge (256px):** `https://raw.githubusercontent.com/Promeduz/steamstore/main/flipworld/support_badge_256.png`
- **Ironheart Item (256px):** `https://raw.githubusercontent.com/Promeduz/steamstore/main/flipworld/item_ironheart_256.png`


These URLs can be used directly in Steam store pages, HTML, or any other application that accepts image URLs.

## Adding Assets for New Games

1. Create a new folder in the repository with your game name
2. Add your assets to that folder
3. Commit and push:
   ```bash
   git add [game-name]/
   git commit -m "Add assets for [game-name]"
   git push
   ```
4. Update the README.md with information about the new game's assets
