# D-light
A lightweight disassembler with linear sweep disassembly algorithm

# How to use

`./dlight -a -u malwr`

```
usage: dlight [-a] [-h] [-r] [-u] [-b bits]
               [-e bytes] [-k start,bytes] [-p vendor] file
   -a activates auto sync
   -u same as -b 32
   -b 16, -b 32 or -b 64 sets the processor mode
   -h displays this text
   -e skips <bytes> bytes of header
   -k avoids disassembling <bytes> bytes from position <start>
   -p selects the preferred vendor instruction set (intel, amd, cyrix, idt)
```