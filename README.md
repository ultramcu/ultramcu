```text
$ ./ultramcu --boot
[0.000] ULTRA·MCU ▸ MCS-51 @ 11.0592 MHz ▸ power-on reset OK
[ OK ] insmod c.ko ............. close to the metal
[ OK ] insmod mcu.ko ........... bare-metal native (it's in the name)
[ OK ] insmod go.ko ............ ships tested libs on pkg.go.dev
[ OK ] harness: AI co-proc attached ▸ I command, it executes
[ OK ] bughunter: scan ......... reproducible fixes, upstreamed
[ OK ] mount /dev/curiosity .... rw
        ┌────────┐
   ──▶──┤   µC   ├──▶──  cat /proc/self
        └────────┘        └─▶ "Harnessner"
ready ▸ _
```
