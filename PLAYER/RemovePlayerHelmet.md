# REMOVE_PLAYER_HELMET

## Declaration
```cpp
// 0x5CF1303D
void REMOVE_PLAYER_HELMET(int playerIndex, bool forceRemove);
```

### Arguments
- **int:** playerIndex
- **bool:** forceRemove

### Results

## Description
Lets the helmet of the player's character come off. With `forceRemove` set to `true` it is removed right away. With `false` it stays on for now and comes off as usual, for example when the player gets out of a vehicle that is not a motorbike.