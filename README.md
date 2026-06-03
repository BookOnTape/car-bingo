# 🚗 Car Bingo

A road trip bingo maker for kids. Pick a category, customize your items, and generate a fully self-contained offline game file with real brand logos.

**Live:** <https://bookontape.github.io/car-bingo>

## How it works

1. Open the live link above
1. Pick a category (Car Brands, Store Signs, Animals, Car Colors, Road Signs, or Custom)
1. Edit the item list however you like
1. Click **Build My Bingo Game**
1. Save the generated HTML file — it works offline forever, logos and all

The maker fetches favicons for brand categories and bakes them into the output as base64, so the saved game needs zero network connection.

## Categories

|Category     |Image source                  |
|-------------|------------------------------|
|🚗 Car Brands |Favicons fetched at build time|
|🛒 Store Signs|Favicons fetched at build time|
|🦁 Animals    |Emoji — no internet needed    |
|🎨 Car Colors |Emoji — no internet needed    |
|🚦 Road Signs |Emoji — no internet needed    |
|✏️ Custom     |Emoji — build your own        |

## Game features

- **New Board** — shuffles a fresh random layout from your item pool
- **Clear Stamps** — resets stamps, same board
- **Print Board** — clean print layout, stamp-free, ready for paper play
- Tap any cell to stamp it; get 5 in a row for BINGO + confetti

## Enabling GitHub Pages

In your repo settings → Pages → Source: **Deploy from branch** → `main` → `/ (root)`

The site will be live at `https://bookontape.github.io/car-bingo` within a minute or two.