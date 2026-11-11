# GET_CHAR_PROP_INDEX

## Declaration
```cpp
// 0x3AC85DB1
void GET_CHAR_PROP_INDEX(int charIndex, int position, int* propIndex);
```

### Arguments
- **int:** charIndex
- **int:** position

### Results
- **int*:** propIndex

## Description
Returns the prop the char wears at the given position (see `SET_CHAR_PROP_INDEX`), or -1 if there is none. While the char sits in a vehicle with a roof, position 0 returns -1 because the game takes hats off there. `GET_CHAR_PROP_TEXTURE_INDEX` returns the texture of the prop.