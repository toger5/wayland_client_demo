# wayland client demo
simple c++ wayland demo inspired by [weston/clients/simple-shm.c](https://cgit.freedesktop.org/wayland/weston/tree/clients/simple-shm.c)

## Build
```
make
```

* It requires `clang`.
```
sudo apt-get install clang
```

## Run
```
./wayland_client_demo
```

* If you click any where in the window, it's closed.

## Background
* I tried to add this sample to Chromium, but faild. [the CL](https://codereview.chromium.org/1752723003/).