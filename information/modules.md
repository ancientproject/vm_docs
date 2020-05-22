# Modules

{% hint style="info" %}
**Note**: Only entry module has accept top level instructions
{% endhint %}

```ocaml
; entry_module.asm
#use "./test.asm"
.call.i !{testFunction()}
```

```c
; test.asm
.sig @testFunction(void) -> void
    .mva &(0x9) &(0xB) <| $(0x0)
.ret
```

#### Using project module in local 

```ocaml
#use "./local-module.asm"
```

#### Using global module

```ocaml
#use "global-module"
```

#### Use list modules

{% hint style="warning" %}
**Note:** Currently not implemented
{% endhint %}

```ocaml
#use ["m1", "m2", "m3"]
```

#### See also

{% page-ref page="../instructions/.mva/" %}

{% page-ref page="../instructions/.call.i.md" %}





