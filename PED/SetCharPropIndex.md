# SET_CHAR_PROP_INDEX

## Declaration
```cpp
// 0x5FE95249
void SET_CHAR_PROP_INDEX(int charIndex, int position, int newPropIndex);
```

### Arguments
- **int:** charIndex
- **int:** position
- **int:** newPropIndex

### Results

## Description
Puts a prop (an extra model like a hat or glasses) on the char at the given position, with texture 0. Same as `SET_CHAR_PROP_INDEX_TEXTURE` with texture 0.

| position | Anchor |
| --- | --- |
| 0 | Head (hats, helmets) |
| 1 | Eyes (glasses) |
| 2 | Ears |
| 3 | Mouth |
| 4 | Left hand |
| 5 | Right hand |
| 6 | Left wrist |
| 7 | Right wrist |
| 8 | Hip |
| 9 | Left foot |
| 10 | Right foot |

A char wears at most two props at a time. If it already wears two props at other positions, nothing happens: remove one with `CLEAR_CHAR_PROP` first. Each position takes the props 0 to 7, higher numbers are ignored. If the model has no such prop, nothing is shown, see `GET_NUMBER_OF_CHAR_PROP_VARIATIONS`.

While the char sits in a vehicle with a roof, the game takes the prop at position 0 off and puts it back on when the char gets out. A helmet also replaces the prop at position 0 and brings it back when it comes off.

Other players see the props of your own character at the positions 0 to 7 with the textures 0 to 6.