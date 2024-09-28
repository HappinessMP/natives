# SET_PLAYER_MOOD_PISSED_OFF

## Declaration
```cpp
// 0x5E061170
void SET_PLAYER_MOOD_PISSED_OFF(int playerIndex, int secondsDuration);
```

### Arguments
- **int:** playerIndex
- **int:** secondsDuration

### Results

## Description
Will piss the player off for duration of seconds.

The player will be rude and push people out of the way when pissed off. The players mood will go back to normal when the timer runs out of when SET_PLAYER_MOOD_NORMAL is called.