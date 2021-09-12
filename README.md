# Zero-Board

This board does nothing specifically.  It is designed to be a ready-at-hand circuit board that can be easily programmed to do many different jobs.

It runs on an ATtiny84 with an Arduino bootloader and a 6-pin interface to a standard USB to TTL module.  Many of the parts called out on the board may be populated with several alternative components.  The NPN high-current output transistors may be replaced by darlington devices or N-Channel MOSFET's. The inputs may be digital or analog with a provision for a resistor divider for higher voltages.  These inputs may also act as serial data inputs, serial data outputs, or TTL digital outputs.

One input is opto coupled using any one of several pin compatable 6-pin devices.  Two of the high current outputs are current sinks which allows them to activate devices of any voltage up to the limit of the part you choose.  One output is a voltage source for 5 volts, and, with a simple trace cut, can be a high side switch for an outside voltage.

A 10-position screw terminal does all the connections to the outside world.  Although on 1/10th inch centers, these connectors are rated for up to gage 12 wire.
