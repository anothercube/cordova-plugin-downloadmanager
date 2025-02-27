# cordova-plugin-downloadmanager
A Cordova plugin to download file in system's default download manager

Forked from: https://github.com/vasani-arpit/cordova-plugin-downloadmanager

## Supported Platforms

 - Android (SDK >= 11)

 ## Installation

### CLI
 ```
 cordova plugin add https://github.com/vasani-arpit/cordova-plugin-downloadmanager
 ```

### Config.xml ( build.phonegap.com )
```
<plugin name="github-cordova-plugin-downloadmanager" spec="https://github.com/anothercube/cordova-plugin-downloadmanager" source="git" />
```

 ## How to Use 

 ```
 //after device is ready
var fail = function (message) {    
    alert(message)
}
var success = function (data) {
        console.log("succes");
}
cordova.plugins.DownloadManager.download("Your URL to download", 'Your filename with extension', success, fail);
 ```

## Result

![screenshot](./screenshot/downloadplugin.gif)

_**If this plugin helps your project then don't forget to ⭐ star the repo.**_

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
