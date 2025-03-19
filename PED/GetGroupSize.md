# GET_GROUP_SIZE

## Declaration
```cpp
// 0x45EE4E9A
void GET_GROUP_SIZE(int groupIndex, int* hasLeader, int* numberOfFollowers);
```

### Arguments
- **int:** groupIndex

### Results
- **int*:** hasLeader
- **int*:** numberOfFollowers

## Description
Gets the number of leaders (1 or 0) and the number of followers (in the range 0-7) that are in the relevant group.