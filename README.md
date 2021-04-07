| :bangbang: | **This repository is no longer maintained. Everything has been igrated to be a part of [air-light dev theme](https://github.com/digitoimistodude/air-light).**  |
|:------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------|

# Air-light theme release automation for WordPress.org

This repository contains the automation scripts for testing and releasing air-light in [WordPress.org Theme Directory](https://wordpress.org/themes/air-light/).

These scripts is for Dude personnel and backup purposes only, but contain no sensitive data.

Check out [air-light](https://github.com/digitoimistodude/air-light) to see dev-versions and documentation.

## Usage

Make sure `zip` package is installed on macOS.

1. Run `sh air_move_out.sh` to test if [Theme Check](https://fi.wordpress.org/plugins/theme-check/) passes the tests
2. Run `sh air_pack.sh` after all tests have passed
3. [Upload](https://wordpress.org/themes/upload/) air-light.zip to Theme Directory (needs access rights in wordpress.org)
4. Run `sh air_move_in.sh` to move back the dev-files to continue developing air-light further.

Have fun!
