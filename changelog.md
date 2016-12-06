# 0.1.2

### Enhancements
* Compress with 18bits vs 19bits
* Reworked dropped packet detection and emit of packets.

### Bug Fixes
* Fix bug where ganglionServer example would hang on scan if no board found.
* Fix bug where node process would not disconnect on windows.
* Fix unhandled promise where server would call search start twice.

# 0.1.1

### New Features
* Add function for starting, `.accelStart()`, and stopping, `.accelStop()`, accelerometer.

### Bug Fixes
* Impedance was outputting on verbose instead of debug.

# 0.1.0

Initial release