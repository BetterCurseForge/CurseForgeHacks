# CurseForge Hacks!

## Remove Advertisements from the CurseForge desktop application;

Unpack CurseForges `app.asar`.

Edit `app/dist/desktop/desktop.js`.

Find line `35985`, or search for `"curseforge-ad": !0,`.

Replace `"curseforge-ad": !0,` with `"curseforge-ad": !1,`.
