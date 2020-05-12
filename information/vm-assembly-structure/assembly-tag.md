# Assembly tag

### Example: **EF0119JG00** 

* EF  - Tag of vm assembly, first 2 byte in file
* 01 - Version
* 0 - not signed assembly, 1 - signed assembly
* 9 - any arch CPU
* A - 2010 year, J - 2019
* A - january, G - june

#### Regex

```erlang
(EF)([0-9]{2})([0-1])([0-9])([A-Z])([A-Z])[0-9]{2}
```

