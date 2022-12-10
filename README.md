### Lawnchair 12.1

Lawnchair is a free, open-source home app for Android. Taking Launcher3

To build with Lawnchair add this line in device.mk
```bash
   # Lawnchair
   $(call inherit-product-if-exists, vendor/lawnchair/lawnchair.mk)
```
