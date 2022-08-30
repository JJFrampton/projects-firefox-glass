# Glass Project

Complete the following steps with the firefox browser

### Setup
- navigate to "about:support"
- find "Profile Directory"
- back up entire profile dir elsewhere
- clone this project inside the profile dir, renaming to "chrome"
```
git clone git@github.com:JJFrampton/projects-firefox-glass.git "${PROFILE_DIR}"/chrome
```

### Enable
- navigate to "about:config"
- ensure "toolkit.legacyUserProfileCustomizations.stylesheets" is set to true

### Restart Firefox
- after restart, navigation & url bar should still be accessable with ctrl+L
