parking_lot_mpsc
================

[![Build Status](https://travis-ci.org/infincia/parking_lot_mpsc.svg?branch=master)](https://travis-ci.org/infincia/parking_lot_mpsc)

This is a port of the Rust std::sync::mpsc module, using the [parking_lot](https://crates.io/crates/parking_lot)
concurrency types rather than those in the standard library.

It is a work in progress and may not be stable at all. In particular, several
impl !Sync/!Send lines are commented out right now.
