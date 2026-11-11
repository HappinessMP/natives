# GET_NUMBER_OF_CHAR_DRAWABLE_VARIATIONS

## Declaration
```cpp
// 0x3C293296
int GET_NUMBER_OF_CHAR_DRAWABLE_VARIATIONS(int charIndex, int componentNumber);
```

### Arguments
- **int:** charIndex
- **int:** componentNumber

### Results
- **int**

## Description
Returns how many drawables the model of the char has for the given component, 0 if it has none. See `SET_CHAR_COMPONENT_VARIATION` for the component numbers.

The drawables that exist are counted. If the numbering of the model's files has a gap (for example `_003` is missing), the highest drawable numbers are not below this count.