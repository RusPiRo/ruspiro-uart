# Changelog

## :peach: v0.4.0

- ### :wrench: Maintenance

  - update travis pipeline build to support convenient publishing
  - implement `core::fmt::Write` for both Uart types to enable them to be used with the latest `ruspiro_console::Console`
  - upgrade the dependency for `ruspiro_register` and add `ruspiro_mmio_register` crate
  - add MIT licencing in addition to Apache-2.0

## :banana: v0.3.1

- ### :detective: Fixes

  - remove `asm!` macro usages and replace with `llvm_asm!`
  - use `cargo make` to stabilize cross-platform builds
