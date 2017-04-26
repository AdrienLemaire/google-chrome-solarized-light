# Google Chrome Solarized Light theme

Used https://chrome.google.com/webstore/detail/solarized-dark/kedemblecjmofcmppbecaagebmokigml as model to build this theme.

Find existing theme location with:

```
$ for f in `find ~/.config/google-chrome/Default/Extensions -name "manifest.json"`;[[ ! -z $(cat $f|grep -i theme) ]] && echo $f
```
