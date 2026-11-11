# SET_POLICE_DISPATCH_REDUCED

## Declaration
```cpp
// 0x08FF52BF
void SET_POLICE_DISPATCH_REDUCED(bool reduced);
```

### Arguments
- **bool:** reduced

### Results

## Description
Sets how many police officers are sent after the local player when they have a wanted level.

`true` (default) uses the multiplayer numbers of the original game: half of the singleplayer amount (at least one officer) and no extra cars once the player has left the wanted area. `false` uses the singleplayer numbers, so noticeably more police units come.

The setting only affects the client that calls it. To use it for all players, call it in the [scriptInit](https://happinessmp.net/docs/scripting/events#scriptinit) event.