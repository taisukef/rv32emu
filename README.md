# RISC-V RV32I[MAC] emulator for learning with hand-assemble

This is a RISC-V emulator for the RV32I architecture, based on [TinyEMU](https://bellard.org/tinyemu/)
and stripped down for RV32I only.

How to compile it:
```shell
$ gcc -O3 -Wall emu-rv32i-test.c -o emu-rv32i-test
```

Run:
```shell
$ ./emu-rv32i-test
```

How to compile it: (RV32C)
```shell
$ gcc -O3 -Wall emu-rv32i-test-c.c -o emu-rv32i-test-c
```

Run:
```shell
$ ./emu-rv32i-test-c
```

## How to build RISC-V toolchain on MacOS

```shell
$ brew tap riscv/riscv
$ brew install riscv-tools
```

## How to use ELF

see also https://github.com/sysprog21/rv32emu  

## Blog

シンプルなシミュレーターとハンドアセンブルで始める、RISC-Vマシン語はじめのいっぽ  
https://fukuno.jig.jp/2691  

RV32C対応  
https://fukuno.jig.jp/2722  
