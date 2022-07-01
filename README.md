# Electric Liftgate Firmware

Please contact Tech Support if you are not sure which firmware you should flash.

## [Model S Electric Frunk](https://evoffer.com/product/model-s-electric-frunk/)
| Version | Hardware | Variant A | Variant B | Variant C |
| --- | --- | --- | --- | --- |
| v2 | Silver casing ECU | 360 | 361 | / |
| MARK 3.0 | Basic waterproof ECU<br>4-pin signal wire<br>2-section strut | F11 | F18 | / |
| MARK 3.1 | Advanced waterproof ECU<br>4-pin signal wire<br>2-section strut | F23 | F22 | / |
| MARK 3.2 | Advanced waterproof ECU<br>6-pin signal wire<br>2-section strut | F23 | F22 (Box v21x)<br>F2018 (Box v25x) | / |
| MARK 5.0 | Advanced waterproof ECU<br>Landing Check<br>6-pin signal wire<br>3-section strut | / | / | F46 (Box v21x)<br>F2021 (Box v25x) |

```
Last Update: 2022-05-08
```

## [Model X Electric Frunk](https://evoffer.com/product/model-x-electric-frunk/)
Version | Hardware | Variant A | Variant B |
| --- | --- | --- | --- |
| v2 | Silver casing ECU | 293A | / |
| MARK 3.0 | Basic waterproof ECU<br>4-pin signal wire<br>2-section strut | F17 | / |
| MARK 3.1 | Advanced waterproof ECU<br>4-pin signal wire<br>2-section strut | F44 | / |
| MARK 3.2 | Advanced waterproof ECU<br>6-pin signal wire<br>2-section strut | F44 (Box v21x)<br>F2019 (Box v25x) | / |
| MARK 5.0 | Advanced waterproof ECU<br>Landing Check<br>6-pin signal wire<br>3-section strut | / | F47 (Box v21x)<br>F2020 (Box v25x) |

```
Last Update: 2022-05-08
```

## [Model 3 Electric Frunk](https://evoffer.com/product/model-3-electric-frunk/)
| Version | Hardware | Variant A | Variant B | Variant C |
| --- | --- | --- | --- | --- |
| v2 | Silver casing ECU | 330 (Box v17x3 w/o touch screen close)<br>337A (Box v17x3 w/ touch screen close)<br>337 (Box v17x4) | / | / |
| MARK 3.0 | Basic waterproof ECU<br>4-pin signal wire<br>2-section strut | F14i | / | / |
| MARK 3.1 | Advanced waterproof ECU<br>4-pin signal wire<br>2-section strut | F26 (Purchased before 2020/10)<br>F351 (Purchased after 2020/10) | / | / |
| MARK 3.2 | Advanced waterproof ECU<br>6-pin signal wire<br>2-section strut | F351 (Box v21x)<br>F2010 (Box v25x) | / | / |
| MARK 4.0 | Basic waterproof ECU<br>Landing Check<br>4-pin signal wire<br>2-section strut | / | F16i | / |
| MARK 4.1 | Advanced waterproof ECU<br>Landing Check<br>4-pin signal wire<br>2-section strut | / | F29 (Box v1500)<br>F3007 (Box v1501)<br>F39 (Box v21x) | F392 (Box v1501)<br>F39 (Box v21x) |
| MARK 4.2 | Advanced waterproof ECU<br>Landing Check<br>6-pin signal wire<br>2-section strut | / | F42 (Box v21x)<br>F2013 (Box v25x) | F42 (Box v21x)<br>F2013 (Box v25x) |

```
Last Update: 2022-04-30
```

## [Model Y Electric Frunk](https://evoffer.com/product/model-y-electric-frunk/)
| Version | Hardware | All Variants |
| --- | --- | --- |
| MARK 3.0 | Basic waterproof ECU<br>4-pin signal wire<br>Silicon casing strut | F15C |
| MARK 4.0 | Basic waterproof ECU<br>Landing Check<br>4-pin signal wire<br>Silicon casing strut | F15C |
| MARK 4.1 | Advanced waterproof ECU<br>Landing Check<br>4-pin signal wire<br>Silicon casing strut | F28 (Box v1500)<br>F3105 (Box v1501)<br>F33 (Box v21x) |
| MARK 4.2 | Advanced waterproof ECU<br>Landing Check<br>6-pin signal wire<br>Silicon casing strut | F41 (Box v21x)<br>F2017 (Box v25x) |
| MARK 5.0 | Advanced waterproof ECU<br>Landing Check<br>6-pin signal wire<br>3-section strut | F41 (Box v21x)<br>F2017 (Box v25x) |

```
Last Update: 2022-04-01
```

## [Model S Electric Tailgate](https://evoffer.com/product/model-s-electric-tailgate/)
| Version | All Variants |
| --- | --- |
| v2 | 189 |

```
Last Update: 2020-11-30
```

## [Model 3 Electric Tailgate](https://evoffer.com/product/model-3-electric-tailgate/)
| Version | All Variants |
| --- | --- |
| v1 | 263 (purchased before 2019/07)<br>305P (purchased after 2019/07) |
| v2 | 298 (purchased before 2020/02)<br>321 (purchased after 2020/02) |
| MARK 2.5 | 502W (purchased before 2021/07)<br>686B (purchased after 2021/07) |
| MARK 3.0 | A2018 |

```
Last Update: 2022-07-01
```

## Software Update
### Step 1 - Preparing Memory Card
Prepare a microSD (32GB or below capacity is preferred).
Make sure it is in FAT32 format.

### Step 2 - Getting the Update File
Get the update file ready.
Rename the file to `update.yst` and place it under the root of the microSD.
Eject it from the card reader afterwards.

### Step 3 - Flashing the Update
*Procedure for older ECU design with firmware file only.* -
[(YouTube Tutorial)](https://youtu.be/WVAIoss6fbk)

Insert the microSD into the control unit.
The red LED will be flashing rapidly.
Wait until the LED becomes solid and eject the microSD.

*New ECUs (v250+ for Electric Frunk; MARK 3.0+ for Model 3 Electric Tailgate) come with a new firmware system that contains two update files (firmware and config).* -
[(YouTube Tutorial)](https://youtu.be/s2w4y5JVml8)

To flash the `update.yst`, you need to disconnect the power of ECU for 30 seconds, insert the SD card and reconnect the power.
The red LED will be flashing rapidly. Wait until the LED becomes solid and eject the microSD.

To flash the `config.yx`, keep the ECU connecting to power and insert the SD card.
The red LED will be flashing slowly.
Wait until the LED becomes solid and eject the microSD.

### Complete! Test the System
The LED should be flashing constantly now and you are all set!


