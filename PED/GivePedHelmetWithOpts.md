# GIVE_PED_HELMET_WITH_OPTS

## Declaration
```cpp
// 0x3B6E1D1E
void GIVE_PED_HELMET_WITH_OPTS(Ped ped, boolean keepHelmet);
```

### Arguments
- **Ped:** ped
- **boolean:** keepHelmet

### Results

## Description
Puts a helmet on the char. The helmet is the last prop at position 0 of the model (see `SET_CHAR_PROP_INDEX`), so models without props at position 0 cannot wear one. Not every char may wear a helmet, see also `ENABLE_PED_HELMET` and `ENABLE_ALL_PED_HELMETS`.

A prop at position 0 (a hat) is taken off and comes back when the helmet comes off. Nothing happens if the char already wears two props and none of them at position 0.

With `keepHelmet` set to `false`, chars without a player model take the helmet off by themselves after a while when they are not on a motorbike. Getting out of a vehicle that is not a motorbike always takes it off.