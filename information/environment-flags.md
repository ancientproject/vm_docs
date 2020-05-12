# Environment flags

## Environment flag for VM

```erlang
- VM_TRACE         : 1\0    - enable or disable trace logging (default 0)
- VM_ERROR         : 1\0    - enable or disable error logging (default 1)
- VM_KEEP_MEMORY   : 1\0    - when halt cpu disable or enable clearing memory table (default 0 - clearing)
- VM_MEM_FAST_WRITE: 1\0    - enable or disable fast-write mode to devices (see fast-mode addressing)
- C69_BIOS_HPET    : 1\0    - enable using hardware hper timer (default 0)
- VM_WARMUP_DEV    : 1\0    - enable warm-up devices on plug-connect (default 1)
- VM_SHUTDOWN_DEV  : 1\0    - enable shutdown devices on halting processor (default 1)
- VM_SYM_ENCODING  : "utf8" - set encoding of debug symbols (default "IBM037")
- SKIP_WARNING     : 1\0    - skip display warning (default 0)
```



