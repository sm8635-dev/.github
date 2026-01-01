## sm8635-dev

This organization contains the repositories required to build AOSP-based ROMs for devices based on the Qualcomm Snapdragon 8s Gen 3 (SM8635) platform, specifically the POCO F6 / Redmi Turbo 3.

**Maintainer:** [zenin1504](https://t.me/zenin1504)

**Status:** Currently supports Android 16 QPR2

### Required device specific repositories
#### Xiaomi 'Peridot' family a.k.a POCO F6 and Redmi Turbo 3
* [**Peridot Device tree**](https://github.com/sm8635-dev/device_xiaomi_peridot) (`device_xiaomi_peridot`)
* [**Peridot Vendor tree**](https://github.com/sm8635-dev/vendor_xiaomi_peridot) (`vendor_xiaomi_peridot`)

---

### Kernel repositories
#### SM8635 Kernel (Xiaomi)
* [**Xiaomi SM8635 Kernel source**](https://github.com/sm8635-dev/kernel_xiaomi_sm8635) (`kernel_xiaomi_sm8635`)
* [**Xiaomi SM8635 Kernel Modules**](https://github.com/sm8635-dev/kernel_xiaomi_sm8635-modules) (`kernel_xiaomi_sm8635-modules`)
* [**Xiaomi SM8635 Kernel Devicetrees**](https://github.com/sm8635-dev/kernel_xiaomi_sm8635-devicetrees) (`kernel_xiaomi_sm8635-devicetrees`)

---

### Other required repositories
* [**Xiaomi Hardware**](https://github.com/sm8635-dev/hardware_xiaomi) (`hardware_xiaomi`)

### Required patches
* [**For fixing dolby service crash**](https://github.com/sm8635-dev/frameworks_av/commit/b17a39b6e6359f8cc5174de64dde58115459688d) (`frameworks_av`)
* [**For avoiding SW DAP effects suspend**](https://github.com/sm8635-dev/frameworks_av/commit/09e19c1a215b1bd714e8dff4ca7f04c9e3eb6a50) (`frameworks_av`)
