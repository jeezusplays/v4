To update the static files, run the following command:

```bash
npm run build
```

This will update the content of the `public` folder. To deploy the changes:

1. Navigate to the `public` folder

```bash
cd public
```

2. Ensure that you are on the `gh-pages` branch

```bash
git checkout gh-pages
```

3. Add the changes, commit and push

```bash
git add .
git commit -m "Update static files"
git push origin gh-pages
```
