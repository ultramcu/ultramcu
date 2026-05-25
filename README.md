```text
$ ./ultramcu --boot
[0.000] ULTRA·MCU @ 16MHz ▸ power-on reset OK
[ OK ] insmod c.ko ............. ♥ close to the metal
[ OK ] insmod mcu.ko ........... bare-metal native (it's in the name)
[ OK ] harness: AI co-proc attached ▸ I command, it executes
[ OK ] bughunter: scan ......... reproducible fixes, upstreamed
[ OK ] mount /dev/curiosity .... rw
        ┌────────┐
   ──▶──┤   µC   ├──▶──  cat /proc/self
        └────────┘        └─▶ "Harnessner"
ready ▸ _
```
