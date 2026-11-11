# SET_CHAR_COMPONENT_VARIATION

## Declaration
```cpp
// 0x71A52973
void SET_CHAR_COMPONENT_VARIATION(int charIndex, int componentNumber, int newDrawableNumber, int newTextureNumber);
```

### Arguments
- **int:** charIndex
- **int:** componentNumber
- **int:** newDrawableNumber
- **int:** newTextureNumber

### Results

## Description
Sets the drawable (model part) and the texture of a component (body part) of the char.

| componentNumber | Body part | File name |
| --- | --- | --- |
| 0 | Head | head |
| 1 | Upper body | uppr |
| 2 | Lower body | lowr |
| 3 | Accessories | suse |
| 4 | Hands | hand |
| 5 | Feet | feet |
| 6 | Jacket | jack |
| 7 | Hair | hair |
| 8 | Accessories 2 | sus2 |
| 9 | Teeth | teef |
| 10 | Face | face |

Textures are numbered by the letter in the file name: `a` is 0, `b` is 1 and so on. A model has at most 16 drawables per component.

Nothing happens if the model has no such component or no such drawable. The texture is not checked, use `GET_NUMBER_OF_CHAR_TEXTURE_VARIATIONS` to stay in range.

Other players see the clothes of your own character, except the components 4 (hands), 6 (jacket) and 9 (teeth), and only with the textures 0 to 15 (`a` to `p`). Changes to the character of another player are not sent to anyone.