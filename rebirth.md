# 重生點

### 使用 CodingBar 連接 Minecraft 世界

```python
from CBMC import *
```

### 連接你的角色！

```python
mc = CBMC('janice_kuo',"minecraft.codingbar.ai")
```

* mc 👉 儲存角色資訊
* janice\_kuo 👉 放入你的角色名稱
* minecraft.codingbar.ai 👉 伺服器地址

### 找到一個點

![](.gitbook/assets/image%20%2811%29.png)

```python
from CBMC import *
mc = CBMC('janice_kuo',"minecraft.codingbar.ai")

mc.setSpawnPoint()
```

![](.gitbook/assets/image%20%281%29.png)

### 悄悄跟自己說重生點

```python
from CBMC import *
mc = CBMC('janice_kuo',"minecraft.codingbar.ai")

# mc.setSpawnPoint()

x,y,z = mc.getPos()
mc.say(x,y,z)
# mc.say("你的位置",x,y,z)
```

![](.gitbook/assets/image%20%285%29.png)

![](.gitbook/assets/image%20%289%29.png)

### 跟後臺說說你的位置吧!!

![](.gitbook/assets/image.png)

```python
from CBMC import *
mc = CBMC('janice_kuo',"minecraft.codingbar.ai")

# mc.setSpawnPoint()

x,y,z = mc.getPos()
mc.say(x,y,z)
# mc.say("你的位置",x,y,z)
print(x,y,z)
```

![](.gitbook/assets/image%20%287%29.png)

