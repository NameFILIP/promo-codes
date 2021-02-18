# promo-codes
A list of promo codes for different products to share with friends and family.
* Use mine: https://namefilip.github.io/promo-codes/
* Create yours ⬇️

## How to create your own list

1. Clone the repo
2. Change `src/promo-codes.js` to contain your codes
3. In repository settings setup GitHub Pages to serve from the `/docs` folder of the `master` branch
4. Publish

## How to publish

```
yarn build
rm -rf docs
mv build docs
git add --all
git commit --message "Publish"
git push
```
