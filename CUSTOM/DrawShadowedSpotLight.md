# DRAW_SHADOWED_SPOT_LIGHT

## Declaration
```cpp
// 0x32BF9598
void DRAW_SHADOWED_SPOT_LIGHT(float x, float y, float z, float dirX, float dirY, float dirZ, int r, int g, int b, float range, float intensity, float innerCone, float outerCone, int lightIndex);
```

### Arguments
- **float:** x
- **float:** y
- **float:** z
- **float:** dirX
- **float:** dirY
- **float:** dirZ
- **int:** r
- **int:** g
- **int:** b
- **float:** range
- **float:** intensity
- **float:** innerCone
- **float:** outerCone
- **int:** lightIndex

### Results

## Description
Same as `DRAW_SPOT_LIGHT`, but the light casts shadows.

Direction is in world space and does not need to be normalized. The cone angles are in degrees: the light is full inside `innerCone` and fades out up to `outerCone` (at most 89). Colour channels are 0 to 255. Nothing is drawn with a range of 0 or a direction of length 0.

The light only exists for the current frame, call it every frame it should show. It is only drawn on this client: to show it to everyone, let every client draw it (for example after an event).

Give every shadowed light its own `lightIndex` and keep it the same from frame to frame, the shadow belongs to it. Lights with the same index share a shadow, also across resources. The game has room for 8 shadowed lights at a time, shared with its own, and gives them to the nearest ones first. A new light gets its shadow after a short moment, so keep drawing it every frame. Shadow casting lights are expensive, use few of them. Without shadows in the graphics settings the light is drawn without a shadow. With FusionFix installed, the local player does not cast a shadow from these lights (other peds, vehicles and objects still do).