
# DG icons v1

--------------------------------------------------------------------------------

## The Icons

  - DG_red ![DG Red](/v1/png/DG_red128.png)
  - DG_blu ![DG Blu](/v1/png/DG_blu128.png)

## File info

  - `DG_red.vtf` & `DG_blu.vtf` are saved in `DTX5` format `128 x 128` pixels in size.

  - `uncrushed` files saved in `BGRA8888` format and `256 x 256` pixels in size.

  - `crushed` files saved in `DTX5` format and `256 x 256` pixels in size.

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

If you use these in your project, you will want to edit the associated `"$basetexture"` line in each VMT file to match your project path and filenames for the files you use.

```
"Sprite"
{
"$spriteorientation" "vp_parallel"
"$spriteorigin" "[ 0.50 0.50 ]"
"$basetexture" "dg/DG_red"
}
```
