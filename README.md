# Axii - Witcher 3 plugin loader

> [!TIP]\
> Move `target/x86_64-pc-windows-msvc/release/dinput8.dll` to `bin/x64_dx12`
> 
> Move `target/x86_64-pc-windows-msvc/release/axii.dll` to `bin/whse`, plugins go into `bin/whse/plugins`
>
> Plugin entry point:
> ```rust
> #[no_mangle]
> unsafe extern "C" fn plugin() {}
> ```

Rust Witcher 3 DLL injection example using `dinput8` proxying `DirectInput8Create`.
