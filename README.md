## About Fork
This project forked from <a href="https://github.com/ammargitham/WallFlow">WallFlow</a>
## To Do
- [ ] Sort by size
- [ ] Fix download error
- [ ] Clear search history

---

<div align="center">
  <img width="200" height="200" src=".github/assets/icon.svg" alt="WallFlow" title="WallFlow">
  <h1>WallFlow</h1>
  <div align="center">
    <a href="https://github.com/ammargitham/WallFlow/releases/latest">
      <img src="https://img.shields.io/github/v/release/ammargitham/wallflow.svg?style=for-the-badge&logo=GitHub&labelColor=black&label=Github&color=black" alt="Github">
    </a>
  </div>
  <div align="center">
    <a href="https://f-droid.org/packages/com.ammar.wallflow/">
      <img src="https://img.shields.io/f-droid/v/com.ammar.wallflow?style=for-the-badge&logo=fdroid&logoColor=%23b1eb0b&label=f-droid (Regular)&labelColor=%23217ad3&color=%23217ad3" alt="F-Droid">
    </a>
    <a href="https://f-droid.org/packages/com.ammar.wallflow.plus/">
      <img src="https://img.shields.io/f-droid/v/com.ammar.wallflow.plus?style=for-the-badge&logo=fdroid&logoColor=%23b1eb0b&label=f-droid (Plus)&labelColor=%23217ad3&color=%23217ad3" alt="F-Droid">
    </a>
  </div>
  <div align="center">
    <a href="https://github.com/ammargitham/WallFlow/actions/workflows/codeql.yml">
      <img src="https://img.shields.io/github/actions/workflow/status/ammargitham/wallflow/codeql.yml?style=for-the-badge&label=CodeQL" alt="CodeQL" title="CodeQL">
    </a>
    <a href="https://hosted.weblate.org/projects/wallflow/">
      <img src="https://img.shields.io/weblate/progress/wallflow?style=for-the-badge" alt="Weblate" title="Weblate">
    </a>
  </div>
  <br/>
  <p>
  A wallpaper app for Android with beautiful wallpapers from <a href="https://wallhaven.cc/">wallhaven.cc</a>, <a href="https://reddit.com/">Reddit</a>. Designed with <a href="https://m3.material.io/">Material Design 3</a> and supports wide screen devices like tablets.
  </p>
</div>
<br/>
<div align="center">
  <img alt="devices" title="Devices" src=".github/assets/devices.png" width="500">
</div>

## Downloads
<div align="center">
<a href="https://github.com/ammargitham/WallFlow/releases/latest">
  <img height="80" alt="Get it on GitHub" title="Get it on GitHub" src="./.github/assets/get-it-on-github.png" />
</a>

|                                                                                                           Regular                                                                                                           |                                                                                                               Plus                                                                                                               |
|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
|                     [<img height="80" alt="Get it on GitHub" title="Get it on GitHub" src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" />](https://f-droid.org/packages/com.ammar.wallflow/)                      |                     [<img height="80" alt="Get it on GitHub" title="Get it on GitHub" src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" />](https://f-droid.org/packages/com.ammar.wallflow.plus/)                      |
| [<img height="80" alt="Get it on IzzyOnDroid" title="Get it on IzzyOnDroid" src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png" />](https://apt.izzysoft.de/fdroid/index/apk/com.ammar.wallflow/) | [<img height="80" alt="Get it on IzzyOnDroid" title="Get it on IzzyOnDroid" src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png" />](https://apt.izzysoft.de/fdroid/index/apk/com.ammar.wallflow.plus/) |

\*[_What's the difference between Regular and Plus?_](#regular-vs-plus)

</div>

## Screenshots

<div align="center">

| <img src="./src/base/fastlane/metadata/android/en-US/images/phoneScreenshots/1.png" alt="Home" width="150"> | <img src="./src/base/fastlane/metadata/android/en-US/images/phoneScreenshots/2.png" alt="Filters" width="150"> | <img src="./src/base/fastlane/metadata/android/en-US/images/phoneScreenshots/2_reddit.png" alt="Filters" width="150"> | <img src="./src/base/fastlane/metadata/android/en-US/images/phoneScreenshots/3.png" alt="Wallpaper Info" width="150"> |
|:-----------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------:|
|                                                 <b>Home</b>                                                 |                                            <b>Wallhaven Filters</b>                                            |                                                 <b>Reddit Filters</b>                                                 |                                                 <b>Wallpaper Info</b>                                                 |

| <img src="./src/base/fastlane/metadata/android/en-US/images/phoneScreenshots/4.png" alt="Search History" width="150"> | <img src="./src/base/fastlane/metadata/android/en-US/images/phoneScreenshots/5.png" alt="Crop and Set Wallpaper" width="150"> | <img src="./src/base/fastlane/metadata/android/en-US/images/phoneScreenshots/6.png" alt="Settings 1" width="150"> |
|:---------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------:|
|                                                 <b>Search History</b>                                                 |                                                 <b>Crop and Set Wallpaper</b>                                                 |                                                  <b>Settings</b>                                                  |

</div>

## Features

- Supports wallhaven.cc and Reddit
- Multi-pane layout for tablets and other wide screen devices
- Auto wallpaper changer
- Save searches
- Favorite wallpapers
- Local Wallpapers
- Use saved searches, favorites, and local wallpapers for auto wallpaper changer
- Search history
- [Plus] Smart wallpaper cropping using on-device object detection powered by [Tensorflow Lite](https://www.tensorflow.org/lite/).
  - Supports adding your own TFLite models. You can find more models [here](https://tfhub.dev/s?deployment-format=lite&module-type=image-object-detection/).
- Search results caching to reduce api calls
- Options to tweak the wallpaper grid layout
- QuickSettings tile, shortcut and broadcast to quickly change wallpaper
- Dynamic theme (Material You)
- Supports multi-display environments (eg. when connected to external monitors)

## Regular vs Plus

Two versions are provided (both free and open-source)

- Regular version without the Object detection feature (smaller apk size).
- Plus version with the Object detection feature. (Since Tensorflow adds around 8MB native libs to the apk size).

**All other features are same in both versions.**

## Broadcast details (for Tasker and similar apps)

- Package:
  - For Regular: `com.ammar.wallflow`
  - For Plus: `com.ammar.wallflow.plus`
- Action: `com.ammar.wallflow.ACTION_CHANGE_WALLPAPER`

ADB command:

- For Regular: `am broadcast --user 0 -a com.ammar.wallflow.ACTION_CHANGE_WALLPAPER com.ammar.wallflow`
- For Plus: `am broadcast --user 0 -a com.ammar.wallflow.ACTION_CHANGE_WALLPAPER com.ammar.wallflow.plus`

## Roadmap

- [ ] Support foldables inner and outer screens together
- [ ] More theme colors
- [ ] Learn from favorites (on-device) and suggest wallpapers
- [ ] Support Windows using [Kotlin multiplatform](https://kotlinlang.org/docs/multiplatform.html).

## Help with translations
<a href="https://hosted.weblate.org/engage/wallflow/">
  <img src="https://hosted.weblate.org/widget/wallflow/287x66-grey.png" alt="Translation status" />
</a>

## Built using

- [Jetpack Compose](https://developer.android.com/jetpack/compose/)
- [Material Design 3 components for Compose](https://developer.android.com/jetpack/compose/designsystems/material3)
- [Compose Destinations](https://composedestinations.rafaelcosta.xyz/)
- [Hilt](https://developer.android.com/training/dependency-injection/hilt-android/)
- [Room](https://developer.android.com/training/data-storage/room/)
- [Datastore](https://developer.android.com/topic/libraries/architecture/datastore/)
- [Retrofit](https://square.github.io/retrofit/)
- [Coil](https://coil-kt.github.io/coil/)
- [Telephoto](https://github.com/saket/telephoto/)
- [Paging 3](https://developer.android.com/topic/libraries/architecture/paging/v3-overview/)
- [Accompanist](https://google.github.io/accompanist/)
- [WorkManager](https://developer.android.com/topic/libraries/architecture/workmanager/)
- [My fork](https://github.com/ammargitham/easycrop/) of [EasyCrop](https://github.com/mr0xf00/easycrop/)
- [Tensorflow Lite](https://www.tensorflow.org/lite/)
- [Cloudy](https://github.com/skydoves/Cloudy/)
- [partial-kt](https://github.com/MateriiApps/partial-kt/)
- [Ktlint](https://pinterest.github.io/ktlint/) using [Spotless](https://github.com/diffplug/spotless) plugin
- [Mockk](https://mockk.io/)
- Some more AndroidX libraries. Please see the [build.gradle](./app/build.gradle.kts) file.

## License

```
WallFlow
Copyright (C) 2023  Ammar Githam

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
