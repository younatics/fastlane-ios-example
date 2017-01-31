# fastlane-ios-example
## Fastlane iOS Example for Beta, Release

### Simple Descriptions
* Automatically distribute Crashlytics in Beta, Tesflight in Release
* Automatically increment build number (eg.4.10.19/iosbeta/4.10.19(3) -> 4.10.19/iosbeta/4.10.19(4))
* If you want to increment version number, use `increment_version_number`
* Make git tag group with your build version (eg. 4.10.19/iosbeta/4.10.19(3)) if you distribute with fastlane
* Get commit message between former version tag and HEAD

### Used Features
* `ensure_git_status_clean`
* `get_info_plist_value`
* `increment_build_number`
* `get_build_number`
* `get_version_number`
* `set_info_plist_value`
* `cert`
* `sigh`
* `pem`
* `gym`
* `commitMessage`
* `testflight`
* `crashlytics`
* `commit_version_bump`
* `add_git_tag`
* `push_to_git_remote`

### Installation
* add `.gitignore` and change your settings in Appfile, Fastfile and Deliverfile

