---
'@astryxdesign/theme-butter': patch
'@astryxdesign/theme-y2k': patch
'@astryxdesign/cli': patch
---

[feat] Butter's and Y2K's badges take the element corners, as their buttons and inputs do: 8px in Butter and square in Y2K, instead of pill corners. The CLI's bundled copies of both themes change the same way. To keep pill badges, extend the theme with `components: {badge: {base: {borderRadius: '9999px'}}}`.

@josephfarina
