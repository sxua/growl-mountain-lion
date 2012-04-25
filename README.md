# Mountain Lion notification style for Growl

Originally created by [Benjamin Crozat](http://dribbble.com/benjamincrozat) on [Dribbble](http://dribbble.com/shots/475237-Mountain-Lion-DP-2-Growl-Theme), but have some bugs, which I have fixed.

Original style:

![Original style](http://pix.am/ypM8.png "Original style")

Fixed style:

![Fixed style](http://pix.am/uUy0.png "Fixed style")

## Installation

```
cd
mkdir -p ~/Library/Application\ Support/Growl/Plugins
git clone git://github.com/sxua/growl-mountain-lion.git
cp -R ~/growl-mountain-lion/Mountain\ Lion.growlStyle ~/Library/Application\ Support/Growl/Plugins/
(optional) rm -rf ~/growl-mountain-lion
```

## TODO

* Original ML notifications animation. _(Animation is done, but there's no shadow and border because of that. Also, close button placed behind notification box in that case.)_