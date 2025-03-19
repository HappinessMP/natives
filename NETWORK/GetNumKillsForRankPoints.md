# GET_NUM_KILLS_FOR_RANK_POINTS

## Declaration
```cpp
// 0x239C0EEC
int GET_NUM_KILLS_FOR_RANK_POINTS(int modelHash);
```

### Arguments
- **int:** modelHash

### Results
- **int**

## Description
Return how many times the local player has killed a char using the specified char model, all kills of chars with models not registered are tracked separately and returned as a combined total.