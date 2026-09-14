# The Minish Cap 3DS Chinese v1.3-E21

## Added

- Added a packaged Chinese user guide covering installation and every lower-screen function.

## Fixed

- Prevented the reported doorway crash seen when rolling into the entrance. The crash dump showed an invalid player-item ID (0x48) indexing past the dispatch table and branching to 0x40000000. Invalid IDs are now removed before dispatch, creation paths reject malformed IDs, and every valid player-item ID has a matching sprite definition.
- Unified Chinese and Latin lower-screen labels on the bundled 12 px font, with white glyphs and a full black outline.
- Replaced the mixed-language Load State confirmation with a concise Chinese confirmation dialog.
- Corrected the map control direction: close view shows “缩小”, while the full map shows “放大”.
- Enlarged dungeon, item, settings, and submenu red title chips with balanced padding.
- Reworked title chips with a beveled red face and matching lower/right depth layer.
- Kept the rolling-barrel BG2 affine scene on the mature software renderer to prevent a black upper screen.
- Fixed widescreen dialogue tearing.
- Fixed incorrect or repeated Chinese area names.
- Fixed the L/R tutorial button pictures.

