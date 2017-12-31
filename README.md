## TWRP device tree for Galaxy S7 edge (International & Canadian Exynos)

Add to `.repo/local_manifests/hero2lte.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/hero2lte" name="android_device_samsung_hero2lte" remote="TeamWin" revision="android-6.0" />
</manifest>
```

Then run `repo sync` to check it out.

To build:

```sh
. build/envsetup.sh
lunch omni_hero2lte-eng
make -j5 recoveryimage
```

Kernel sources are available at: https://github.com/jcadduono/android_kernel_samsung_universal8890/tree/twrp-6.0
