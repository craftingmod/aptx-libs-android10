# aptX libraries for Android 10

This module places `libaptx` in `/system/product/`. If you aren't using `system-as-root`, use other modules which is for Oreo & Pie.

Original work by [**Flex1911**](https://github.com/Flex1911/aptx-libs-android10)

This module adds aptX libraries to uncertified/unsupported/GSI devices (Ex. *RP2*) with Android 10.

armv7 library is from https://github.com/multiwirth/aptx-magisk-module-armv7.

## Disclaimer
*Every device needs a license to support aptX, so using this module is theoretically illegal.*

`persist.vendor.bt.a2dp_offload_cap` should include `*-aptx-aptxhd-*` for use. Check `/vendor/build.prop` for that.