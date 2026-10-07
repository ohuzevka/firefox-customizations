# My Firefox customizations
How it looks like on Windows 10:
![Screenshot on Windows 10](/img/Screenshot_Win10.png)

# Settings
- Untick `Show sidebar`

# Extensions
- [Sidebery](https://addons.mozilla.org/en-US/firefox/addon/sidebery/)
- [Undo close tab](https://addons.mozilla.org/en-US/firefox/addon/undoclosetabbutton/)
- [I still don't care about cookies](https://addons.mozilla.org/en-US/firefox/addon/istilldontcareaboutcookies/)
- [Video Speed Controller](https://addons.mozilla.org/en-US/firefox/addon/videospeed/)
- [Bypass Google Redirect Notice](https://addons.mozilla.org/en-US/firefox/addon/bypass-google-redirect-notice/)

# Themes
- [Simple style fox 2](https://addons.mozilla.org/en-US/firefox/addon/simple-style-fox-2/)

# about:config mods
Type `about:congig` to address bar.

### Enable modifications using chrome css files
`toolkit.legacyUserProfileCustomizations.stylesheets` = `true`

### Disable fullscreen transitions and popups
`full-screen-api.transition-duration.enter` = `0 0`

`full-screen-api.transition-duration.leave` = `0 0` 

`full-screen-api.warning.timeout` = `0`

# userChrome.css mods
1. Type `about:support` to address bar
2. Find `Profile Folder` and click `Open Folder`
3. Inside the profile folder create a new folder named `chrome`
4. Clone this repo: `https://github.com/MrOtherGuy/firefox-csshacks` into the `chrome` folder
5. Copy the `userChrome.css` file into the `chrome` folder