# SET_PED_COMPONENTS_TO_NETWORK_PLAYERSETTINGS_MODEL

## Declaration
```cpp
// 0x5C3053C0
void SET_PED_COMPONENTS_TO_NETWORK_PLAYERSETTINGS_MODEL(Ped ped);
```

### Arguments
- **Ped:** ped

### Results

## Description
Dresses a char with a multiplayer model (`M_Y_MULTIPLAYER`, `F_Y_MULTIPLAYER`) like the multiplayer character saved in the game profile of this client (the character menu of the original game). The look always comes from the client that calls it, so on another player's character it shows your own saved character.