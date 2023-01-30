# ItyFuzz
Fast hybrid fuzzer for EVM, MoveVM, etc.


### Building
```bash
cd cli/
cargo build --release
```

### Run
```bash
./cli --contract-glob './demo/*'
```

### Z3 Installation (macOS)
```bash
git clone https://github.com/Z3Prover/z3 && cd z3
python scripts/mk_make.py --prefix=/usr/local
cd build && make -j64 && sudo make install
```