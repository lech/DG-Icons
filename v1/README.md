
# DG icons v1

--------------------------------------------------------------------------------

## The Icons

  - DG_red ![DG Red](/v1/png/DG_red128.png)
  - DG_blu ![DG Blu](/v1/png/DG_blu128.png)

## File info

  - `uncrushed` files saved in `BGRA8888` format and `256 x 256` pixels in size.
  - `crushed` files saved in `DTX5` format and `256 x 256` pixels in size.
    - `DG_red.vtf` & `DG_blu.vtf` are in `DTX5` format at `128 x 128px`

### VTF info

Flags set in all files.

```
Mipmap Filter: Box
Sharpen Filter: Sharpen Soft
Mipmaps: True
Thumbnail: True
Clamp S
Clamp T
No Level of Detail
```

## VMT info

If you use these in your own project, you will need to edit the associated `"$basetexture"` line in each VMT file to match your path setup.

```
"Sprite"
{
"$spriteorientation" "vp_parallel"
"$spriteorigin" "[ 0.50 0.50 ]"
"$basetexture" "dg/DG_red"
}
```
