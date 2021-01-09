# GTuner Scripts for RingCon input interceptor
## Titan II Switch Overview
* Joycons would be emulated as a Switch Pro Controller

## Titan II Switch Settings

## GTuner Concepts
### Input Translator
* Remap any controls
* Why bother?
	* In switch, both left and right joy cons contribute to GYRO values. It's hard to distingush which one contributes to the GYRO value, so disabling one's GYRO values would reduce noise significantly.

## GTuner References
### JoyCon wireless pairing
   1. `Device Configuration` panel -> Wireless Pairing
   1. Press and hold the power button on the JoyCon until the light is flashing
   1. Wait for the light on JoyCon becomes stable

### Device Monitor 
* A tab to check input mappings between JoyCon/RingCon to GTuner

### Remapper
* Configure controller mapping

### Persistent Memory
* Usage
* init()
	* pmem_load();
	* pmem_read(index, &var);
* main
	* pmem_write(index, var);
	* pmem_save();

## Note