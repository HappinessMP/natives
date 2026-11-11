# GET_CHAR_PROP_TEXTURE_INDEX

## Declaration
```cpp
// 0x1529BE4A
void GET_CHAR_PROP_TEXTURE_INDEX(int charIndex, int position, int* textureIndex);
```

### Arguments
- **int:** charIndex
- **int:** position

### Results
- **int*:** textureIndex

## Description
Returns the texture (0 is `a`) of the prop the char wears at the given position, or -1 if there is none. See `SET_CHAR_PROP_INDEX` for the positions and `GET_CHAR_PROP_INDEX` for the prop.