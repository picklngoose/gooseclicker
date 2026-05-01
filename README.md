# 🪿 HONK CLICKER

A minimalist idle clicker game. Click the goose, earn honks, buy upgrades, conquer the world with noise.

## 🎮 Gameplay

- **Click** the goose to earn honks
- **Buy upgrades** to increase honks per click or generate honks automatically
- Watch your goose empire grow 🏞️

### Upgrades

| Upgrade | Type | Effect |
|---|---|---|
| Gosling | Auto | +0.5 honks/sec |
| Goose Pond | Auto | +3 honks/sec |
| Goose Parade | Auto | +15 honks/sec |
| Migration Flock | Auto | +80 honks/sec |
| Louder Honk | Click | +1 honk/click |
| Megaphone | Click | +5 honks/click |
| HONKSTORM | Click | +25 honks/click |

## 🚀 Deploy to GitHub Pages

### First-time setup

1. **Push this repo to GitHub.**

2. **Enable GitHub Pages** in your repo settings:
   - Go to `Settings → Pages`
   - Under **Source**, select **GitHub Actions**
   - Save

3. **Push to `main`** — the workflow fires automatically and your game will be live at:
   ```
   https://<your-username>.github.io/<your-repo-name>/
   ```

### Manual deploy

You can also trigger a deploy manually from the **Actions** tab → **Deploy Honk Clicker to GitHub Pages** → **Run workflow**.

## 📁 File structure

```
.
├── index.html                        # The entire game (single file)
└── .github/
    └── workflows/
        └── deploy.yml                # GitHub Actions CI/CD
```


