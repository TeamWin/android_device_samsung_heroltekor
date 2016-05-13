## TWRP device tree for Galaxy S7 (Korea)

Add to `.repo/local_manifests/heroltekor.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/heroltekor" name="android_device_samsung_heroltekor" remote="TeamWin" revision="android-6.0" />
</manifest>
```

Then run `repo sync` to check it out.

Kernel sources are available at: https://github.com/jcadduono/nethunter_kernel_herolte/tree/twrp-6.0

