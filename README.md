### py-spy
---
https://github.com/benfred/py-spy


```py
// tests/scripts/thread_reuse.py
import time
import threading

while True:
  th = threading.Thread(target = lambda: time.sleep(.5))
  th.start()
  th.join()
```

```
```

```
```

