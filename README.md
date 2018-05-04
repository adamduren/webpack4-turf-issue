# To reproduce

```
git clone https://github.com/adamduren/webpack4-turf-issue.git
cd webpack4-turf-issue
npm install
npm run build
```

```
ERROR in ./node_modules/@turf/meta/index.mjs
1002:15-25 Can't import the named export 'lineString' from non EcmaScript module (only default export is available)
 @ ./node_modules/@turf/meta/index.mjs
 @ ./src/index.js
```