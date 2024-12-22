## 🧩 ReVanced Patches

ReVanced Extended Patches. 

See the [documentation](https://github.com/inotia00/revanced-documentation#readme) to learn how to apply patches and build ReVanced Extended apps.

## 📋 List of patches in this repository

### [📦 `com.google.android.youtube`](https://play.google.com/store/apps/details?id=com.google.android.youtube)

### [📦 `com.google.android.apps.youtube.music`](https://play.google.com/store/apps/details?id=com.google.android.apps.youtube.music)

### [📦 `com.google.android.apps.photos`](https://play.google.com/store/apps/details?id=com.google.android.apps.photos)

## 📝 JSON Format

This section explains the JSON format for the [patches.json](patches.json) file.

Example:

```json
[
  {
    "name": "Miniplayer",
    "description": "Adds options to change the in app minimized player, and if patching target 19.16+ adds options to use modern miniplayers.",
    "use":true,
    "compatiblePackages": {
      "com.google.android.youtube": [
        "18.29.38",
        "18.33.40",
        "18.38.44",
        "18.48.39",
        "19.05.36",
        "19.16.39"
      ]
    },
    "options": []
  },
  {
    "name": "Certificate spoof",
    "description": "Enables YouTube Music to work with Android Auto by spoofing the YouTube Music certificate.",
    "use":true,
    "compatiblePackages": {
      "com.google.android.apps.youtube.music": [
        "6.20.51",
        "6.29.59",
        "6.42.55",
        "6.51.53",
        "7.16.53"
      ]
    },
    "options": []
  },
  {
    "name": "Spoof features",
    "description": "Spoofs the device to enable Google Pixel exclusive features, including unlimited storage.",
    "use":true,
    "compatiblePackages": {
      "com.google.android.apps.photos": "ALL"
    },
    "options": []
  }
]
```
