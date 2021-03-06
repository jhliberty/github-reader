# github-reader [![Build Status](https://travis-ci.org/azu/github-reader.svg?branch=master)](https://travis-ci.org/azu/github-reader)

Github Client - Viewer for [Notifications](https://github.com/notifications "Notifications") and [News Feed](https://github.com/ "GitHub")

![ScreenShot](http://cl.ly/image/2v053R0Y0s0a/2014-04-29%2022_38_04.gif)

Built with [node-webkit](https://github.com/rogerwang/node-webkit "node-webkit").

## Features

* Viewer for mixed [Notifications](https://github.com/notifications "Notifications") and [News Feed](https://github.com/ "GitHub")
* Growl Notification(for Mac only, relate issue - [Implement desktop notifications](https://github.com/rogerwang/node-webkit/issues/27 "Implement desktop notifications [$50] · Issue #27 · rogerwang/node-webkit"))
* `J`,`K` scroll shortcut
* `O` : open in browser
* `Ctrl + R` reload
* `Ctrl + f` : toggle search bar - [gif](http://gyazo.com/0c5ed12adcc0b22e50457d1e7e6f82e3)

## Installation

**[Download latest binary](https://github.com/azu/github-reader/releases/latest)**

Multi-platform support

- Windows
- Mac OS X
- Linux 32,64bit

### Config

![token](http://monosnap.com/image/xNMXVDIlfH6Lom2Q2DMDKxPbc3kLaJ.png)

* Create [New personal access token](https://github.com/settings/tokens/new "New personal access token")
    * require **scopes** are `notifications` and `user`

![config](http://monosnap.com/image/Dgh7zSUetiJTNuQQ55w76CYVur7G0h.png)

* Open `Config` in Github-Reader.app
    * Input Github **username**
    * Input personal access token
* Save & Reload

## Develop

``` sh
npm install
bower install
```

[Run apps](https://github.com/rogerwang/node-webkit/wiki/How-to-run-apps "run apps") with node-webkit.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

MIT
