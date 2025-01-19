# GET_POSITION_OF_ANALOGUE_STICKS

## Declaration
```cpp
// 0x4F7F4FAE
void GET_POSITION_OF_ANALOGUE_STICKS(int PadNumber, int* ReturnLeftX, int* ReturnLeftY, int* ReturnRightX, int* ReturnRightY);
```

### Arguments
- **int:** PadNumber (usually 0)

### Results
- **int*:** ReturnLeftX
- **int*:** ReturnLeftY
- **int*:** ReturnRightX
- **int*:** ReturnRightY

## Description
Gets the position of analogue stickes between -128 and 128. A value of 0 means that the stick is in the central position.