# Android `/system/media` files collection

This repository is an attempt to collect all `/system/media` files (alarms, notifications and ringtones) I've discovered over the years of using different Android devices.

There are some useful modifications I've made to the source files:
- Added ID3 tags with vendor and file name, as well as `ANDROID_LOOP` tag for alarms and ringtones
- Normalized loudness to -14 LUFS (with stereo channels normalized independently)
- Resampled to 48000 Hz
- And renamed them so that it's easier to browse the collection.

This repository will be updated over time, so feel free to clone it onto your device and fetch updates using git.

__NOTE: I am not the owner of the media files provided. Their respective authors are specified both in each file name and in the ID3 tags.__