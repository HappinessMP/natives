# SET_PED_HELMET_TEXTURE_INDEX

## Declaration
```cpp
// 0x6AC14091
void SET_PED_HELMET_TEXTURE_INDEX(Ped ped, int index);
```

### Arguments
- **Ped:** ped
- **int:** index

### Results

## Description
Sets the texture (0 is `a`) of the next helmet the char gets. A helmet the char already wears keeps its texture. With a negative index or one the helmet does not have, every new helmet gets a random texture (default).