# MP_GET_VARIATION_SETUP

## Declaration
```cpp
// 0x3775138E
int MP_GET_VARIATION_SETUP(Ped ped, int componentid, int choice, int* drawable, int* texture);
```

### Arguments
- **Ped:** ped
- **int:** componentid
- **int:** choice

### Results
- **int**
- **int*:** drawable
- **int*:** texture

## Description
Returns the drawable and texture of a choice in the multiplayer character menu of the original game (choice 0 up to `MP_GET_AMOUNT_OF_VARIATION_COMPONENT` minus 1). Both are -1 if the choice does not exist.

Only works with `M_Y_MULTIPLAYER` and `F_Y_MULTIPLAYER`: the first result is 0 for other models, otherwise 1.