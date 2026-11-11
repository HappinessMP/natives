# GET_NUMBER_OF_CHAR_PROP_VARIATIONS

## Declaration
```cpp
// 0x64A37E6B
int GET_NUMBER_OF_CHAR_PROP_VARIATIONS(int charIndex, int position);
```

### Arguments
- **int:** charIndex
- **int:** position

### Results
- **int**

## Description
Returns how many props the model of the char has at the given position, 0 if it has none. See `SET_CHAR_PROP_INDEX` for the positions. Valid props are 0 up to this number minus 1.

At position 0, the last prop is the helmet the char gets on a motorbike or through `GIVE_PED_HELMET`. It is included in this number.