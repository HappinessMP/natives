# FORCE_AIR_DRAG_MULT_FOR_PLAYERS_CAR

## Declaration
```cpp
// 0x554053ED
void FORCE_AIR_DRAG_MULT_FOR_PLAYERS_CAR(int playerIndex, float multiplier);
```

### Arguments
- **int:** playerIndex
- **float:** multiplier

### Results

## Description
Force higher air drag mult on any car or bike the player uses until the mission ends or this command is called again with 1.0, fDragMult range 1.0 - 15.0  (5.0 is standard for high air resistance zones on the map).