# make-stable-appimage-release

Makes an stable release of your AppImage and commits the latest version to the repository, this action needs a file in the current working dir called `./appinfo` with the following information:

```
X-AppImage-Name=APPNAME     # used for the release name
X-AppImage-Version=VERSION  # used for the release version
```

The release tag will contain the version of the application plus the current date in the following format: `VERSION@%Y-%m-%d_%s`.

The action will also commit to a `./LATEST_VERSION` file to the top of the repository containing the version of the app.
