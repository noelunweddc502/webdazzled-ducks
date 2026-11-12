# Webdazzled Ducks · The Family Collective

Live site: https://noelunweddc502.github.io/webdazzled-ducks/

## Turn on photo uploads (one time, about 10 minutes)
1. Make a free account at cloudinary.com.
2. Copy your **Cloud name** from the Dashboard.
3. Settings → Upload → Upload presets → Add preset:
   - Name: `webdazzled`
   - Signing mode: **Unsigned**
   - Folder: `webdazzled-ducks`
   - Save.
4. Settings → Security → **Restricted media types**: uncheck **Resource list** (lets the gallery list approved photos).
5. In `index.html`, fill in `CLOUD_NAME` and `UPLOAD_PRESET` near the bottom, then upload the file again.

## Approve photos for the gallery
New photos arrive tagged `pending` and stay hidden.
In Cloudinary → Media Library, open a photo → Tags → add `approved`.
It shows in the gallery within about a minute. Delete anything you don't want.
