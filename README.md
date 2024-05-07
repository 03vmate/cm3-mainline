# Usage

Clone BSP and this repo into available profiles
```
git clone --recursive https://github.com/radxa-repo/bsp.git
git clone https://github.com/03vmate/cm3-mainline.git bsp/linux/cm3-mainline
```

Run build
```
cd bsp
./bsp -C linux cm3-mainline radxa-cm3-io
```

Clone rbuild
```
cd ..
git clone --recursive https://github.com/radxa-repo/rbuild.git
cd rbuild
./rbuild --kernel ../bsp/linux-image-6.8.9-1-cm3-mainline_6.8.9-1_arm64.deb radxa-cm3-io
```
