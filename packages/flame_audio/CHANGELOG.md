## 2.0.5

 - Update a dependency to the latest release.

## 2.0.4

 - **FIX**: Update sdk constraints to >=3.0.0 ([#2554](https://github.com/flame-engine/flame/issues/2554)). ([2f71e06e](https://github.com/flame-engine/flame/commit/2f71e06eb86ffc65cd459c4d722eee2470be13e5))

## 2.0.3

 - **FIX**: Update sdk constraints to >=3.0.0 ([#2554](https://github.com/flame-engine/flame/issues/2554)). ([2f71e06e](https://github.com/flame-engine/flame/commit/2f71e06eb86ffc65cd459c4d722eee2470be13e5))
 - **FIX**: Solve warnings from 3.10.0 analyzer ([#2532](https://github.com/flame-engine/flame/issues/2532)). ([b41622db](https://github.com/flame-engine/flame/commit/b41622db8faa7559328f83f8f1d93ec4c6386961))

## 2.0.2

 - **FIX**: Release instead of dispose audioplayer in play ([#2513](https://github.com/flame-engine/flame/issues/2513)). ([e699b259](https://github.com/flame-engine/flame/commit/e699b259e99619bb97fe370ce0679157e65eb42b))

## 2.0.1

 - **REFACTOR**: Add new lint rules ([#2477](https://github.com/flame-engine/flame/issues/2477)). ([dbda37b8](https://github.com/flame-engine/flame/commit/dbda37b81a9a7411559a6ba919ffbda6018b85c2))

## 2.0.0

> Note: This release has breaking changes.

 - **BREAKING** **FEAT**: Update AudioPlayers to ^4.0.0 ([#2482](https://github.com/flame-engine/flame/issues/2482)). ([47372087](https://github.com/flame-engine/flame/commit/47372087f218e9c00d0fec82084f6edc7cbee5af))

Migration instructions:

AudioPool has moved to AudioPlayers, but we still export it from `flame_audio`,
so the only thing you have to do if you import AudioPool directly is to
change the import to:
`import 'package:flame_audio/flame_audio.dart';`

## 1.4.1

 - **DOCS**: Update funding links ([#2420](https://github.com/flame-engine/flame/issues/2420)). ([8294a2a1](https://github.com/flame-engine/flame/commit/8294a2a15638c504aa2b77f967f5963af1f23c2c))
 - **DOCS**: Update all README files for the bridge packages to be consistent and not broken ([#2402](https://github.com/flame-engine/flame/issues/2402)). ([5e8ecf54](https://github.com/flame-engine/flame/commit/5e8ecf5450688b1287368b3fbc7b0e718a29fce4))

## 1.4.0

 - Bump to audioplayers v3.0.0
 
## 1.3.5

 - Update a dependency to the latest release.

## 1.3.4

## 1.3.3

## 1.3.2

 - Update a dependency to the latest release.

## 1.3.1

 - Update a dependency to the latest release.

## 1.3.0

> Note: This release has breaking changes.

 - **FEAT**: Move to Flutter 3.0.0 and Dart 2.17.0 ([#1713](https://github.com/flame-engine/flame/issues/1713)). ([2a41d0d6](https://github.com/flame-engine/flame/commit/2a41d0d683391194b7209c47bde91199ab7a663e))
 - **BREAKING** **FEAT**: Update flame_audio to AP 1.0.0 ([#1724](https://github.com/flame-engine/flame/issues/1724)). ([d6bf920d](https://github.com/flame-engine/flame/commit/d6bf920d28eea5f08adcba2601104271078e7a3d))

## 1.2.0

> Note: This release has breaking changes.

 - **FEAT**: Move to Flutter 3.0.0 and Dart 2.17.0 ([#1713](https://github.com/flame-engine/flame/issues/1713)). ([2a41d0d6](https://github.com/flame-engine/flame/commit/2a41d0d683391194b7209c47bde91199ab7a663e))
 - **BREAKING** **FEAT**: Update flame_audio to AP 1.0.0 ([#1724](https://github.com/flame-engine/flame/issues/1724)). ([d6bf920d](https://github.com/flame-engine/flame/commit/d6bf920d28eea5f08adcba2601104271078e7a3d))

## 1.1.0

 - **REFACTOR**: Move to package imports ([#1625](https://github.com/flame-engine/flame/issues/1625)). ([843ddc36](https://github.com/flame-engine/flame/commit/843ddc36249272fcb518b44672e1012307dfa1b5))
 - **FIX**: Removed warnings using flutter v3 ([#1640](https://github.com/flame-engine/flame/issues/1640)). ([69214827](https://github.com/flame-engine/flame/commit/69214827a0edb563468951256eccecab408f89df))
 - **FEAT**: Add more lint rules ([#1703](https://github.com/flame-engine/flame/issues/1703)). ([49252f8e](https://github.com/flame-engine/flame/commit/49252f8ef29aa6b77144dcb97c24346f2f39380b))
 - **FEAT**: Bump to Flutter 2.10.0 ([#1617](https://github.com/flame-engine/flame/issues/1617)). ([beac9013](https://github.com/flame-engine/flame/commit/beac901313456cf0b39b6f4e6459f0feed183614))

## 1.0.2

 - Update a dependency to the latest release.

## 1.0.1

 - Graduate package to a stable release. See pre-releases prior to this version for changelog entries.

## 1.0.1-releasecandidate.1

## [1.0.0]
* Bump to Flame 1.0.0

## [1.0.0-rc.15]
* Bump audioplayers version to 0.20.1

## [1.0.0-rc.1]
* Moved project to the mono-repo
* Updated flame, audioplayers

## [0.1.0-rc5]
* Updated `audioplayers` version
* Updated Flame version
* Add support to null safety

## [0.1.0-rc4]
* Update audioplayers version

## [0.1.0-rc3]
* Bump flame version to rc5, upgrade code to match, update other dependencies
* Add linter and fix code to comply

## [0.1.0-rc2]
* Bump flame version to rc2 and audioplayers version to 0.17

## [0.1.0-rc1]
* First real version, including all necessary files for 1.0.0

## [0.0.1]
* Empty release; in the future all flame audio related code will live here.
