## sm8635-dev

This organization contains the repositories required to build AOSP-based ROMs for devices based on the Qualcomm Snapdragon 8s Gen 3 (SM8635) platform, specifically the POCO F6 / Redmi Turbo 3.

**Maintainer:** [zenin1504](https://t.me/zenin1504)

**Status:** Currently supports Android 16 QPR2

### Repositories
* [**Peridot Device tree**](https://github.com/sm8635-dev/device_xiaomi_peridot) (`device_xiaomi_peridot`)
* [**Peridot Vendor tree**](https://codeberg.org/zenin1504/vendor_xiaomi_peridot) (`vendor_xiaomi_peridot`)
* [**Xiaomi Hardware**](https://github.com/sm8635-dev/hardware_xiaomi) (`hardware_xiaomi`)
* [**Xiaomi SM8635 Kernel Devicetrees**](https://github.com/sm8635-dev/kernel_xiaomi_sm8635-devicetrees) (`kernel_xiaomi_sm8635-devicetrees`)
* [**Xiaomi SM8635 Kernel Modules**](https://github.com/sm8635-dev/kernel_xiaomi_sm8635-modules) (`kernel_xiaomi_sm8635-modules`)
* [**Xiaomi SM8635 Kernel source**](https://github.com/sm8635-dev/kernel_xiaomi_sm8635) (`kernel_xiaomi_sm8635`)

### Required commit for c2 crash
* [**Add Sony's Codec2 service**](https://github.com/sm8635-dev/device_xiaomi_peridot/commit/8d065eeadf1a97e451053a03b0f406f41baeac82) — Sony's C2 service implementation to fix media crashes.
