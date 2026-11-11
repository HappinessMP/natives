# GET_NUMBER_OF_CHAR_TEXTURE_VARIATIONS

## Declaration
```cpp
// 0x6C4113E
int GET_NUMBER_OF_CHAR_TEXTURE_VARIATIONS(int charIndex, int componentNumber, int drawableNumber);
```

### Arguments
- **int:** charIndex
- **int:** componentNumber
- **int:** drawableNumber

### Results
- **int**

## Description
Returns how many textures the given drawable of the component has, 0 if the drawable does not exist. See `SET_CHAR_COMPONENT_VARIATION` for the component numbers.