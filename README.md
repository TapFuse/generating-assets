## Generate assets

* Generate Icons
```shell
ticons icons icon.png -d ./output-icons -p ios,iphone,ipad,android --sdk-version 4.0.0
```
* Generate Splashscreens
```
ticons splashes splash.png -d ./output-splashes -p ios,iphone,ipad,android --sdk-version 4.0.0 -n
```

## Setup tools

Clone repo https://github.com/TapFuse/TiCons-CLI to `~/Projects/TapFuse/`
```shell
cd ~/Projects/TapFuse/TiCons-CLI
npm install
sudo npm link
```

* Install Homebrew
http://brew.sh

* Install ImageMagic
```
brew install imagemagick
```