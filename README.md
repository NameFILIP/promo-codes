# promo-codes
A list of promo codes for different products - https://namefilip.github.io/promo-codes/

## How to create your own list

1. Change `src/promo-codes.js` to contain your codes
2. Setup GitHub Pages to serve from the `/docs` folder of the `master` branch
3. Publish

## How to publish

```
yarn build
rm -rf docs
mv build docs
git add --all
git commit --message "Publish"
git push
```
