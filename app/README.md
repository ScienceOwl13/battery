Development notes:

- logo icons are 20px black/white for theme and 100% vs 50% for active inactive (inside bit only.)
- deploy new version:
    - Update version in `package.json`
    - `npm run build`
    - Create new [release](https://github.com/actuallymentor/battery/releases) with both the `.dmg` and `.zip` (for `electron-updater`)
    - Update [brew formula](https://github.com/Homebrew/homebrew-cask/blob/master/Casks/battery.rb) through`brew bump-cask-pr --version`
