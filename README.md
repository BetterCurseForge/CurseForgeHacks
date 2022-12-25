
# Remove Advertisements from the CurseForge desktop application;
## Not very effective, doesn't *entirely* work. It just helps a little.

Unpack CurseForges `app.asar`.

Edit `app/dist/desktop/desktop.js`.

Find line `35985`, or search for `"curseforge-ad": !0,`.

Replace `"curseforge-ad": !0,` with `"curseforge-ad": !1,`.


# Find & Replace CurseForges colour scheme in desktop.js
## Defaults:
Light: `4D4D4D`

Light 1: `262626`

Light 2 `333333`

Dark: `1A1A1A`

Dark 1: `0D0D0D`


## Example:

Light: `330D71`

Light 1: `4F0E77`

Light 2 `4F0E77`

Dark: `2B073F`

Dark 1: `140216`


## Unified, Black, Colour Scheme Example
Light: `000000`

Light 1: `000000`

Light 2 `000000`

Dark: `000000`

Dark 1: `000000`
