# build khadas openwrt example

## download source again

    git clone https://github.com/hyphop/khadas-openwrt.git
    cd khadas-openwrt

## prepare new rel

    echo REL=19.07.0-rc1 >> scripts/build.conf

## rebuild all for VIM2 + servers variant

    ./scripts/build -r -2 +servers
