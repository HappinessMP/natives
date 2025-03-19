# NETWORK_CHANGE_GAME_MODE

## Declaration
```cpp
// 0x3F054F44
bool NETWORK_CHANGE_GAME_MODE(int gameMode, int maxPlayers, int maxPrivateSlots, int maxTeams);
```

### Arguments
- **int:** gameMode
- **int:** maxPlayers
- **int:** maxPrivateSlots
- **int:** maxTeams

### Results
- **bool**

## Description
Changes the game mode and number of slots of the current session.
Callable only by the host.
Number of slots cannot be reduced from their current number.