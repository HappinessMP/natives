# DRAW_CORONA_WITH_INTENSITY

## Declaration
```cpp
// 0xB663683C
void DRAW_CORONA_WITH_INTENSITY(float x, float y, float z, float radius, int r, int g, int b, float intensity);
```

### Arguments
- **float:** x
- **float:** y
- **float:** z
- **float:** radius
- **int:** r
- **int:** g
- **int:** b
- **float:** intensity

### Results

## Description
Adds a corona (the glowing sprite on a lamp) for this frame, with a brightness of its own. `DRAW_CORONA` always uses the same brightness.

`radius` has the same scale as in `DRAW_CORONA`: 200 is about 1 metre. The `intensity` sets how bright the corona shines, for example 3 to 9 for the lamps of an emergency light bar. Colour channels are 0 to 255. Nothing is drawn with a radius or intensity of 0.

The corona only exists for the current frame, call it every frame it should show. It is only drawn on this client. Scripts can only add coronas while the game's list of coronas for this frame is not nearly full, further ones are not drawn.