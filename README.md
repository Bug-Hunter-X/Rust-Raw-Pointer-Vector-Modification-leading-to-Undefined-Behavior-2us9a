# Rust Raw Pointer Vector Modification leading to Undefined Behavior

This repository demonstrates a common error in Rust: modifying a vector through a raw pointer after its capacity might have changed.  This leads to undefined behavior and potential crashes.

The `bug.rs` file contains the erroneous code.  `bugSolution.rs` shows a safer alternative using safe Rust methods.

This is a critical illustration of why raw pointers should be used with extreme caution in Rust and often avoided in favor of safer abstractions.  Understanding this pattern is vital for writing robust and reliable Rust code.