# `mini-css-extract-plugin` issue repro

Install dependencies and run `npx webpack`.

Based on the `mini-css-extract-plugin` docs, I would expect to the `/dist` folder to look like this:

```
dist
  |_ a.css
  |_ b.css
  |_ main.js
```

But instead, it looks like this:
```
dist
  |_ main.css
  |_ main.js
```
