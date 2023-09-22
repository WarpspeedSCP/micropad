# micropad
zmk config repo for the micropad, a seeed studio xiao BLE based macro pad with encoder support.

Here's the current key config (top right key is encoder click, the encoder is set for volume control):

Base layer:
---
```
┌──────────┬───────────┐
│          │           │
│          │  play/    │
│          │  pause    │
│          │ (vol ctl) │
├──────────┼───────────┤
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
```
┌───────────┬───────────┐
│           │           │
│           │  boot     │
│           │  loader   │
│           │           │
├───────────┼───────────┤
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
