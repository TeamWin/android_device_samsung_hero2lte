## TWRP device tree for Galaxy S7 Edge (International Exynos, SM-G935F)

Add to `.repo/local_manifests/hero2lte.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/hero2lte" name="android_device_samsung_hero2lte" remote="TeamWin" revision="android-6.0" />
</manifest>
```

Then run `repo sync` to check it out.

Kernel sources are available at: https://github.com/jcadduono/nethunter_kernel_herolte/tree/twrp-6.0

