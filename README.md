Clone repo https://github.com/TapFuse/TiCons-CLI to `~/Projects/TapFuse/`
```shell
cd ~/Projects/TapFuse/
npm install
sudo npm link
```

* Generate Icons
```shell
ticons icons icon.png -d ./output-icons -p ios,iphone,ipad,android --sdk-version 4.0.0
```
* Generate Splashscreen
```
ticons splashes splash.png -d ./output-splashes -p ios,iphone,ipad,android --sdk-version 4.0.0 -n
```
