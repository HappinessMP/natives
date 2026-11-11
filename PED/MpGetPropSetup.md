# MP_GET_PROP_SETUP

## Declaration
```cpp
// 0x1C00658B
int MP_GET_PROP_SETUP(Ped ped, int position, int choice, int* propIndex, int* textureIndex);
```

### Arguments
- **Ped:** ped
- **int:** position
- **int:** choice

### Results
- **int**
- **int*:** propIndex
- **int*:** textureIndex

## Description
Returns the prop and texture of a choice for a prop position (see `SET_CHAR_PROP_INDEX`) in the multiplayer character menu of the original game. Choice 0 means no prop, both are -1 then. Other choices return -1 if the model does not have the prop.

Only works with `M_Y_MULTIPLAYER` and `F_Y_MULTIPLAYER`. The first result is 1 if the choice was found (also for choice 0), otherwise 0.