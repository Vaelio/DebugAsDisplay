# DebugAsDisplay

## Example usage

```rust
use debug_as_display::DebugAsDisplay;

#[derive(Debug, DebugAsDisplay)]
enum Test {
    A,
    B
}

fn main() {
    println!("{}", Test::A);
    println!("{}", Test::B);
}
```
