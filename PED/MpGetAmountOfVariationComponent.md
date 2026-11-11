# MP_GET_AMOUNT_OF_VARIATION_COMPONENT

## Declaration
```cpp
// 0x54DD6ACF
int MP_GET_AMOUNT_OF_VARIATION_COMPONENT(Ped ped, int componentid);
```

### Arguments
- **Ped:** ped
- **int:** componentid

### Results
- **int**

## Description
Returns how many choices the multiplayer character menu of the original game offers for a component (see `SET_CHAR_COMPONENT_VARIATION`). Only the components 0, 1, 2, 3, 4 and 7 have choices, other components return 0.

Only works with `M_Y_MULTIPLAYER` and `F_Y_MULTIPLAYER`, other models return 0. The number depends on the model, the episode and the head and upper body the char currently wears.