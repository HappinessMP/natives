# SET_VEHICLE_LIGHT_ENABLED

## Declaration
```cpp
// 0x3FE69E20
void SET_VEHICLE_LIGHT_ENABLED(int carIndex, int light, bool enabled);
```

### Arguments
- **int:** carIndex
- **int:** light
- **bool:** enabled

### Results

## Description
Hides a single light of a vehicle (`false`) or shows it again (`true`). It is cheap enough to be called every frame, for example for strobe lights.

| light | |
| --- | --- |
| 0 | Headlight left |
| 1 | Headlight right |
| 2 | Tail light left |
| 3 | Tail light right |
| 4 | Indicator front left |
| 5 | Indicator front right |
| 6 | Indicator rear left |
| 7 | Indicator rear right |
| 8 | Brake light left |
| 9 | Brake light right |
| 10 | Brake light centre |
| 11 | Reversing light left |
| 12 | Reversing light right |
| 13 | Taxi roof light |

A light can only be hidden, not switched on. A hidden headlight stays dark while the headlights are off anyway, and `FORCE_CAR_LIGHTS` still switches all lights of the vehicle. Not every model has all of these lights. Lights broken by damage stay broken, `true` does not repair them.

The setting only affects the client that calls it, other players still see the light. To show a pattern to everyone, send the state to all players yourself (for example with an event) and let every client run the pattern. Vehicle handles are different on every client, use `GET_NETWORK_ID_FROM_VEHICLE` and `GET_VEHICLE_FROM_NETWORK_ID` to pass a vehicle on. Players who join later need the current state as well.

The setting is lost when the vehicle is deleted on this client. That also happens when the vehicle of another player leaves your range and comes back later, so set it again whenever you get the vehicle from its network id.