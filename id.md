---
description: 每一個方塊都有自己專屬的身分證
---

# 身分證

![](.gitbook/assets/image%20%2812%29.png)

```python
from CBMC import *
mc = CBMC('janice_kuo',"minecraft.codingbar.ai")

x,y,z = mc.getPos()
club_id = mc.getBlock(x,y-1,z)
print(club_id)
```

![](.gitbook/assets/image%20%282%29.png)

![](.gitbook/assets/image%20%286%29.png)

```python
from CBMC import *
mc = CBMC('janice_kuo',"minecraft.codingbar.ai")

x,y,z = mc.getPos()

club1_id = mc.getBlock(x,y-1,z)
club2_id = mc.getBlock(x-1,y-1,z)
club3_id = mc.getBlock(x-2,y-1,z)
print(club1_id)
print(club2_id)
print(club3_id)
```

![](.gitbook/assets/image%20%288%29.png)

