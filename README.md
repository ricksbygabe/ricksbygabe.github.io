# RICKSBYGABE Website V2

## Upload to GitHub

Upload every item from this folder to the ROOT of the `ricksbygabe.github.io` repository:

- index.html
- styles.css
- script.js
- product-data.js
- images folder

Keep all names and folders unchanged.

## Normal inventory updates

Most future updates only require changing `product-data.js`.

### Change stock

```js
stock: 2
```

Change to `1` and the website automatically says `ONLY 1 LEFT`.

For sold out:

```js
stock: 0,
status: "soldout"
```

For coming soon:

```js
stock: 0,
status: "comingsoon"
```

### Change price

```js
price: 145,
oldPrice: 200
```

The old price is crossed out automatically. Use a genuine former or comparison price.

### Add a product

1. Add its photos to the correct image folder.
2. Copy an existing product block in `product-data.js`.
3. Change the product details and image paths.
4. Upload the changed `product-data.js` plus the new images.

For future changes, send ChatGPT the photos, name, category, current price, genuine old/comparison price, sizes, stock count, and status.
