# profile-2

## 開発

```bash
npm run dev
```

## リリース

```
npm run generate
git add -A && git commit -m "build"
git push -f origin `git subtree split --prefix dist`:master
```
