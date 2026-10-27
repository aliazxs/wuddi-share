# Wuddi public share (`/p/{token}`)

Short branded host: **https://wuddi.surge.sh/p/{token}**

Redeploy after editing `index.html`:

```bash
cd store/public-share
npx surge ./ wuddi.surge.sh
```

Requires a free [Surge](https://surge.sh) login (`surge login`). App links use `AppConfig.publicShareBaseUrl`.
