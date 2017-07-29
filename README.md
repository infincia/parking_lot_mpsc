### Rust mpsc channels for [parking_lot](https://crates.io/crates/parking_lot)

This is a port of the Rust std::sync::mpsc module, using the `parking_lot`
concurrency types rather than those in the standard library.

It is a work in progress and may not be stable at all. In particular, several
impl !Sync/!Send lines are commented out right now.
