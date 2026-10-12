# Anthony Michael Perri — Portfolio site

This folder is the whole website. Every page, image and video is already included.

## Put it online with GitHub Pages (free, about 10 minutes)

1. Sign out of your other GitHub account. Create a new account with the username **anthonymichaelperri**.
2. Click **New repository**. Name it exactly **anthonymichaelperri.github.io**. Set it to **Public** and click **Create repository**.
3. On the new repo page, click **uploading an existing file**.
4. Unzip `portfolio-site.zip` on your computer. Open the folder and select **everything inside it**: `index.html`, the other `.html` files, the `assets` folder and this README. Drag all of it into the upload box. `index.html` must sit at the top level, not inside a subfolder.
5. Click **Commit changes**. Wait for the upload to finish, since the videos take a minute.
6. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, then **main**, then **/ (root)**. Click **Save**.
7. After 1–2 minutes the site is live at **https://anthonymichaelperri.github.io**.

## Optional: link previews

When you share the link in iMessage, LinkedIn and similar apps, they show a preview image. That works best with a full web address. In `index.html`, find this line near the top:

    <meta property="og:image" content="assets/og-image.jpg">

and change it to:

    <meta property="og:image" content="https://anthonymichaelperri.github.io/assets/og-image.jpg">

You can edit it directly on GitHub: click the file, then the pencil icon, then Commit.

## Updating later

To replace any file, upload a new one with the same name to the same folder, and it overwrites the old one. Changes go live in about a minute.
