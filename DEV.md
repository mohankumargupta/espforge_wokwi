## How to add firmware

1.  copy diagram.json from example
2. 

```rust
cargo binstall cargo-espflash
cargo espflash save-image --chip esp32c3 firmware.bin
```