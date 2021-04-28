# Silent Hills: P.T

- [x] Framerate Unlock
- [x] 720p Internal Resolution (Currently borked)

## 60 FPS

Not very useful without resolution hack on PS4, Might be useful in the future for PS5 Hardware.

This game uses double buffer vsync! If rendering budget does not meet target, will drop to half refresh rate.

<details> 
<summary>Code (Click to Expand)</summary>

```
be 01 00 00 00 e8 f3 51 2b 00

be 00 00 00 00 e8 f3 51 2b 00
```

</details>

## Resolution Hack (Borked)

<details> 
<summary>Code (Click to Expand)</summary>

```
48 b8 80 07 00 00 38 04 00 00

48 b8 00 05 00 00 d0 02 00 00
```

</details>