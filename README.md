# avr-test-global-asm
```
git clone 
```

## bin crate: avr-test-bin-jmp
```
cd avr-test-bin-jmp
cargo build --release
```

-> no error

## lib crate: avr-test-lib-jmp
```
cd avr-test-lib-jmp
cargo build --release
```

```
error: instruction requires a CPU feature not currently enabled
  |
note: instantiated into assembly here
 --> <inline asm>:4:5
  |
4 |     jmp x
  |     ^
```
