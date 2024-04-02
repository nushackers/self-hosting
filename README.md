To build slides, do

```bash
npm run build -- --base hackertools_materials/self-hosting
```

Then, copy the `dist/` folder into the main subdirectory

```bash
cp -r dist/* ..
```

> Note: This is buggy since slidev was not designed to work in subdirectories, stuff like download is broken.
