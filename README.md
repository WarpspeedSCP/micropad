# micropad
zmk config repo for the micropad, a seeed studio xiao BLE based macro pad with encoder support.


## BOM

| Part Name                                                                                                         | Number required |
| ----------------------------------------------------------------------------------------------------------------- | --------------- |
| Pololu SPDT slide switch (or an equivalent; they're all the same)                                                 | 1x              |
| Seeed Studio Xiao BLE (nRF52840; don't buy the sense variant - it's costlier and useless for this build.)         | 1x              |
| A 300mAh battery (it should be okay even if the dimensions don't match too closely.)                              | 1x              |
| Choc Sunset low profile switches + choc compatible keycaps (I got mine at [lowprokb.ca](https://www.lowprokb.ca)) | 6x              |
| Alps EC11 compatible encoder (I used a KY-040)                                                                    | 1x              |
| 20mm long, 2mm diameter standoffs                                                                                 | 4x              |
| M2x0.4 screws (with your choice of head)                                                                          | 8x              |
| Rubber feet                                                                                                       | 4x              |

## Key Layout

Here's the current key config. Top right key is encoder click (the encoder is set for volume control):

Base layer:
---
```
           ┌───────────┐
           │           │
           │  play/    │
           │  pause    │
           │ (vol ctl) │
┌──────────┼───────────┤
│          │           │
│  page    │  page     │
│  up      │  down     │
│          │           │
├──────────┼───────────┤
│          │           │
│ browser  │ browser   │
│ back     │ forward   │
│          │           │
├──────────┼───────────┤
│          │           │
│  escape  │ xf86      │
│  (layer  │ screen    │
│   tap 1) │ saver     │
│          │ (KP_LOCK) │
└──────────┴───────────┘
```

Settings layer:
---

Empty cells are `&trans`.

```
            ┌───────────┐
            │           │
            │  boot     │
            │  loader   │
            │           │
┌───────────┼───────────┤
│           │           │
│           │           │
│           │           │
│           │           │
├───────────┼───────────┤
│           │           │
│  bt       │  bt       │
│  prev     │  next     │
│  dev      │  dev      │
├───────────┼───────────┤
│           │           │
│           │           │
│           │  bt       │
│           │  clear    │
│           │           │
└───────────┴───────────┘
```
