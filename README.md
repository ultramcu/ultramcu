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

### `whoami`

I write **C** because I like living close to the metal, and I love **MCUs** so
much it ended up in my name — **Ultra MCU**.

My current favorite sport is being a **Harnessner**: I don't just *prompt* AI, I
*harness* it — wiring agents into tight harnesses that drive, measure, verify,
and ship real work. **I command, it executes.**

And when something smells off, I'm a **Bug Hunter** 🐛 — reproduce it, write the
fail-before/pass-after test, fix it, upstream it.

### `cat /etc/modules`

```text
languages   : C · assembly · Go   (+ a little Dart, Rust, Arduino)
silicon     : 8-bit MCUs · ESP · sensors · serial protocols
harness     : multi-agent review · verify-before-commit · bug-hunt swarms
method      : measure first, claim later
```

### `ls ~/ships`  —  things I build

```text
go/   dependency-light, tested Go libraries on pkg.go.dev
        (graphs/A*, serial drivers, image feeds, Thai text/number toolkits, …)
c/    drop-in MCU modules — byte-fed, hardware-agnostic, stdlib-only
```

### `git log --merged --author=ultramcu`  —  selected upstream

```text
fixes merged into well-known projects, e.g.
  • Eclipse Paho        (MQTT clients)
  • golang-jwt / jwt    (token handling)
  • gocsv               (CSV ↔ structs)
  • … and more across the Go (and Dart) ecosystem
```

### `cat /proc/harness`

```text
I treat AI like silicon: give it a clean interface, a strict harness, and a
test bench — then let it run. Agents propose; measurements decide; only
verified work gets committed.
```

<sub><code>// EOF — caught a bug in something I shipped? open an issue. I hunt those for fun.</code></sub>
