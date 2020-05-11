# Flags address

{% hint style="warning" %}
All values are bool in the integer representation
{% endhint %}

| Address Cell | Description |  |
| :--- | :--- | :--- |
| 0x11 | trace logging | \(default 0\) |
| 0x12 | error logging | \(default 1\) |
| 0x13 | when halt cpu disable or enable clearing memory table  |  |
| 0x14 | fast-write mode to devices \(see fast-mode addressing\) |  |
| 0x18 | enable float-mode |  |
| 0x19 | enable stack-forward flag |  |
| 0x20 | control stack flag \(north flag\) |  |
| 0x21 | control stack flag \(east flag\) |  |
| 0x22 | bios read-access flag |  |

```scheme
; enable trace logging
.ldi &(0x11) <| $(0x1)
```

