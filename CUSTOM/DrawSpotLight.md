# DRAW_SPOT_LIGHT

## Declaration
```cpp
// 0xBDBC410C
void DRAW_SPOT_LIGHT(float x, float y, float z, float dirX, float dirY, float dirZ, int r, int g, int b, float range, float intensity, float innerCone, float outerCone);
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

### Results

## Description
Adds a spot light (a cone of light like a searchlight) for this frame. Takes the same values as `DRAW_LIGHT_WITH_RANGE` plus a direction and a cone.

Direction is in world space and does not need to be normalized. The cone angles are in degrees: the light is full inside `innerCone` and fades out up to `outerCone` (at most 89). Colour channels are 0 to 255. Nothing is drawn with a range of 0 or a direction of length 0.

The light only exists for the current frame, call it every frame it should show. It is only drawn on this client: to show it to everyone, let every client draw it (for example after an event).

The light casts no shadow, see `DRAW_SHADOWED_SPOT_LIGHT`.