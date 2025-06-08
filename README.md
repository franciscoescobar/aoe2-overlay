# Disclaimer:
Not all civs logos and unique units assets, newer ones still need to be added.

# AoE2 DE Overlay - Live Match Tracker

A real-time overlay for Age of Empires II: Definitive Edition showing player ratings, civilizations, match history, and game status. Perfect for streamers using OBS!

![{91791F7C-8202-479C-9B1B-3F19FFE90BD6}](https://github.com/user-attachments/assets/e1e9bb26-c49e-46e1-bc8b-5e7b948c0380)

## Quick Start

**Ready to use overlay:** [https://franciscoescobar.github.io/aoe2-overlay/overlay-aoe.html?profileid=2223786](https://franciscoescobar.github.io/aoe2-overlay/overlay-aoe.html?profileid=2223786)

Simply replace `2223786` with your own Profile ID in the URL above.

## How to Use

### Basic URL Structure

You need your Profile ID from aoeinsights.com:

```bash
# Using Profile ID
https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPO-NAME/overlay-aoe.html?profileid=945834
```

### Features

-   ✅ Real-time match tracking
-   ✅ Player ratings (MMR) with changes
-   ✅ Win/Loss indicators
-   ✅ Civilization emblems and unique units
-   ✅ Match history (last 5 games)
-   ✅ Live game status
-   ✅ Map information and game type
-   ✅ Optimized layout for OBS

### OBS Setup

1. Add a **Browser Source** in OBS
2. Use the URL with your profile ID or Steam ID
3. Set Width: 570px, Height: 90px
4. Check "Refresh browser when scene becomes active"

### Finding Your IDs

-   **Profile ID**: Go to https://www.aoeinsights.com/, search your profile, and copy the number from the URL

## Deployment to GitHub Pages

1. Fork or clone this repository
2. Go to your repository settings on GitHub
3. Navigate to "Pages" in the left sidebar
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click Save
7. Your overlay will be available at: `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/overlay-aoe.html`

## Support

For questions or suggestions:

-   Create an issue on GitHub

This was inspired from https://github.com/LucasJappert/ & https://github.com/transparencies/aoe2-rating-overlay
