# PuzzleSlider by TaylorP — To do

_Last updated: 2026-10-22_

Classic sliding-tile puzzle game for Android (Java, package `net.orangebytes.slide`), originally written by TaylorP for orangebytes.net and uploaded here as-is. It uses the old Eclipse/Ant project layout (target android-17, minSdk 8); no changes since July 2022.

## Done
- Full game source imported (169 files): splash screen, main activity, game and options fragments, puzzle model, tile/time/sound/font utilities, flip animations
- Bundled SlidingMenu library project and `android-support-v4.jar`
- Included puzzle pictures, background music and sound effects (`res/raw`)
- Options list with puzzle selection, grid-size switcher, best time / best moves, music and sound toggles
- README with game description and original-author credit (July 2022)

## To do
- [ ] Migrate the Eclipse/Ant project (`build.xml`, `.classpath`, `project.properties`) to Gradle so it opens and builds in current Android Studio
- [ ] Raise `targetSdkVersion` from 16 / `minSdkVersion` from 8 to levels current tooling and the Play Store accept
- [ ] Replace the bundled SlidingMenu library and `android-support-v4.jar` with AndroidX equivalents
- [ ] `OptionsFragment.java:48` TODO: load the puzzle list from shared preferences instead of a hard-coded array
- [ ] `TileUtils.java:12` TODO: move the tile padding constant into a resource
- [ ] Add a LICENSE / link to the original TaylorP source so the reuse terms are clear

## Notes
- Branch: `main`, remote `github.com/desmondknunoo/PuzzleSlider-by-TaylorP`. No uncommitted changes.
- No tests in the project.
