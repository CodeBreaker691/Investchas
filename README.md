# Kharcha — put it on your phone (about 15 minutes, free)

The app is 7 small files. You host them on a free website, then install that website as an app on your phone.

## Option A: GitHub Pages (recommended, the link stays forever)

1. Go to https://github.com and sign up (free).
2. Click **+ → New repository**. Name it `kharcha`, keep it **Public**, then click **Create repository**.
3. On the new repo page, click **uploading an existing file**. Unzip `kharcha.zip` on your laptop and drag in **all 7 files** (not the folder). Click **Commit changes**.
4. Go to **Settings → Pages**. Under *Build and deployment*, pick **Source: Deploy from a branch** → Branch **main** / **(root)** → **Save**.
5. Wait 1–2 minutes and refresh. Your link appears at the top: `https://<your-username>.github.io/kharcha/`

Your expense *data* is never uploaded. It stays on your phone. Only the empty app is public.

## Option B: Netlify Drop (the fastest way)

1. Sign up free at https://app.netlify.com.
2. Open https://app.netlify.com/drop and drag the unzipped `kharcha` folder onto the page.
3. You get a link like `https://something-random.netlify.app`. You can rename it under Site settings.

## Install it on your phone

**Android (Chrome):** open your link → ⋮ menu → **Add to Home screen** / **Install app** → Install.
**iPhone (Safari only):** open your link → **Share** button → **Add to Home Screen** → Add.

Open Kharcha from the home-screen icon from then on. It runs full-screen and works offline.

## Keep your data safe

- All data is stored on the phone, inside the app. Uninstalling the app or clearing Chrome/Safari site data **erases it**.
- About once a month: **Settings → Download backup** (or **Copy backup text** and paste it into a note or email to yourself).
- New phone: install the app again → Settings → **Restore backup**.
- iPhone: always use the home-screen app, not a Safari tab. Safari can clear data for sites you haven't visited in a while.

## Updating the app later

Replace `index.html` in your GitHub repo (or drop the folder on Netlify again). Your data is unaffected. The phone picks up the new version the second time you open the app.
