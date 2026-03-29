Indonesia
setelah melakukan patch, pastikan ini aktif pada defconfig CONFIG_TCP_CONG_ADVANCED=y kemudian tambahkan:
- bbr v3
CONFIG_TCP_CONG_BBR=y

contoh penerapan:
https://github.com/kucingoranye/android_kernel_xiaomi_sdm660_419/commit/578d9205499b194fb9204bef2ec9c610e9403f9d

- bbr plus
CONFIG_TCP_CONG_BBRPLUS=y

contoh penerapan:
https://github.com/kucingoranye/android_kernel_xiaomi_sdm660_419/commit/4fa179075af98a1f0bafde8ccb81bce27115bc1c

English
After patching, make sure to enable CONFIG_TCP_CONG_ADVANCED=y in your defconfig, then add these:

- bbr v3
CONFIG_TCP_CONG_BBR=y

example:
https://github.com/kucingoranye/android_kernel_xiaomi_sdm660_419/commit/578d9205499b194fb9204bef2ec9c610e9403f9d

- bbr plus
CONFIG_TCP_CONG_BBRPLUS=y

example:
https://github.com/kucingoranye/android_kernel_xiaomi_sdm660_419/commit/4fa179075af98a1f0bafde8ccb81bce27115bc1c
