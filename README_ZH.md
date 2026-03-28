# SoccerWindow2 for MSYS2-UCRT64

安装依赖
```sh
pacman -S mingw-w64-ucrt-x86_64-qt5-base \
          mingw-w64-ucrt-x86_64-fontconfig \
          mingw-w64-ucrt-x86_64-glib2 \
```

构建
```sh
mkdir build
cd build
cmake -G "Unix Makefiles" ..
make -j
```
