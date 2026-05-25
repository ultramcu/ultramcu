```text
$ ./ultramcu --boot
[0.000] ULTRA·MCU ▸ power-on reset OK
[0.001] cpu: P89C51 ▸ 8051 core @ 11.0592 MHz
[0.002] uart0 ▸ 9600 8N1 ▸ console up
[0.003] hm6264 ▸ 8K×8 SRAM ▸ XRAM mapped
[0.004] 8255 PPI ▸ ports A/B/C ▸ 24 GPIO up
[ OK ] insmod c.ko ............. close to the metal
[ OK ] insmod mcu.ko ........... bare-metal native (it's in the name)
[ OK ] insmod go.ko ............ ships tested libs on pkg.go.dev
[ OK ] insmod docker.ko ........ build once, run anywhere — zero deps
[ OK ] harness: AI co-proc attached ▸ I command, it executes
[ OK ] bughunter: scan ......... reproducible fixes, upstreamed
[ OK ] mount /dev/curiosity .... rw
        ┌────────┐
   ──▶──┤   µC   ├──▶──  cat /proc/self
        └────────┘        └─▶ "Harnessner"
ready ▸ _
```
