# SET_VEHICLE_EXTRA_VISIBLE

## Declaration
```cpp
// 0x39896246
void SET_VEHICLE_EXTRA_VISIBLE(int carIndex, int extra, bool visible);
```

### Arguments
- **int:** carIndex
- **int:** extra
- **bool:** visible

### Results

## Description
Hides an extra (1 to 9) of a vehicle (`false`) or shows it again (`true`), on this client only. Made for patterns like emergency lights that switch extras many times a second.

The extra is only hidden, not switched off: `IS_VEHICLE_EXTRA_TURNED_ON` still returns `true`, the vehicle is not changed and nothing is sent to other players. An extra that is switched off stays off with `true`. Switch the extras of a light bar on once with `TURN_ON_VEHICLE_EXTRA_NO_REPAIR` (other players see that) and then hide and show them with this native on every client.

To show a pattern to everyone, send its state to all players yourself (for example with an event) and let every client run it. Vehicle handles are different on every client, use `GET_NETWORK_ID_FROM_VEHICLE` and `GET_VEHICLE_FROM_NETWORK_ID` to pass a vehicle on.

The setting is lost when the vehicle is deleted on this client. That also happens when the vehicle of another player leaves your range and comes back later, so set it again whenever you get the vehicle from its network id.