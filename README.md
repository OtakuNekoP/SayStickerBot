# TG_SayStickerBot

Say Sticker.

## Depend

```
sudo apt-get install g++ make binutils cmake
sudo apt-get install libssl-dev libboost-system-dev zlib1g-dev libcurl4-gnutls-dev
sudo apt-get install libcairo2-dev libpango1.0-dev libopencv-dev librsvg2-dev libwebp-dev libsqlite3-dev font-noto
```

```
brew install openssl zlib cmake boost@1.59 pango sqlite
```

tgbot-cpp:
https://github.com/YJBeetle/tgbot-cpp

ArtRobot: 
https://github.com/YJBeetle/ArtRobot

## Build&&Test

    mkdir build && cd build && cmake ..
    make && TOKEN=<TOKEN> ./TG_ThrowItBot

## Run

    TOKEN=<TOKEN> ./TG_ThrowItBot