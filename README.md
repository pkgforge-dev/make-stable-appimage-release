# make-stable-appimage-release

Makes an stable release of your AppImage and commits the latest version to the repository, this action needs:

*  A file in the current working dir called `./appname` which is used for the release name. 

* A file in the current working dir called `./version` which is used for the release version as well as the `LATEST_VERSION` commit to the repository.

The release tag will contain the version of the application plus the current date in the following format: `VERSION@%Y-%m-%d_%s`.
