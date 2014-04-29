# github-reader [![Build Status](https://travis-ci.org/azu/github-reader.svg?branch=master)](https://travis-ci.org/azu/github-reader)

Github Client - Viewer for [Notifications](https://github.com/notifications "Notifications") and [News Feed](https://github.com/ "GitHub")

![img](http://monosnap.com/image/e0vsd8Ujih87QEyaE70FjndnvTogwm.png)

Built with [node-webkit](https://github.com/rogerwang/node-webkit "node-webkit").

## Installation

1. [Downloads](https://github.com/rogerwang/node-webkit#downloads "Downloads") node-webkit
2. Install node-webkit
3. Download [github-reader.nw](https://github.com/azu/github-reader/blob/gh-pages/github-reader.nw?raw=true)
4. Open github-reader.nw

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