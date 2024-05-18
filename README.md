# gdext-rust-template
This repo contains an unofficial minimalist gdext godot-rust project template for game development by following the [godot-rust book](https://godot-rust.github.io/book/intro/hello-world.html) getting started guide.

Make sure to change the libraries section in `rust.gdextension` to specify **your** cargo compilation target:
```
[libraries]
# Linux
linux.debug.x86_64 =     "res://../rust/target/debug/librust.so"
linux.release.x86_64 =   "res://../rust/target/release/librust.so"
# Windows
windows.debug.x86_64 =   "res://../rust/target/debug/rust.dll"
windows.release.x86_64 = "res://../rust/target/release/rust.dll"
# Mac
macos.debug =            "res://../rust/target/debug/librust.dylib"
macos.release =          "res://../rust/target/release/librust.dylib"
macos.debug.arm64 =      "res://../rust/target/debug/librust.dylib"
macos.release.arm64 =    "res://../rust/target/release/librust.dylib"
```
