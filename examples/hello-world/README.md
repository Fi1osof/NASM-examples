## NASM lesson-1. Hello world

## Run
### With package.json
```bash
yarn build
yarn start
```

### Bash
```bash
# Build
nasm -f elf main.asm -o build/main.o
ld -m elf_i386 build/main.o -o build/main
# Run
./ld -m elf_i386 build/main.o -o build/main
```
