# Clarah Birthday Gift ❤️

A cinematic, interactive birthday experience made especially for Clarah.

## Run locally

```bash
npm install
npm run dev
```

Then open the local URL Vite gives you.

## Build

```bash
npm run build
```

## Put it online for free with GitHub Pages

1. Create a new GitHub repository (for example `clarah-birthday-gift`).
2. Upload the contents of this folder to the repository and push them to the `main` branch.
3. GitHub Actions will automatically run the included `.github/workflows/deploy.yml`.
4. In the repository, open **Settings → Pages** and make sure the source is **GitHub Actions**.
5. After the workflow finishes, GitHub will give you the public Pages URL.

The project uses a relative Vite base (`./`) so it works from a GitHub Pages project URL, not only from a custom domain.

## Customize the gift

The main personal content is in `index.html`. Search for `Clarah`, `Dear Clarah`, `reportMini`, and `memoryCard` to change her name, the letter, the medical-report joke, or the four little cards.

The main cinematic animation and replay behavior are in `birthday.js`.

## Replay

The final birthday card has a **Replay from the beginning** button. The smaller **Replay the magic** control also remains available after the cinematic sequence settles.
