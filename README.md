# profile-2

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

## リリース

```
npm run generate
git add -A && git commit -m "build"
git push -f origin `git subtree split --prefix dist`:master
```
