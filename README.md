# na-co's built-in pre amp
Pre amp for embedding in guitar. Replace the output jack with TRS and supply +12V to the ring for use.

https://yokuhizumu.art.blog/

## Connectors
### J1, J2 and U2 (Top view)
- J1: Connect to pickup selector
- J2: Connect to LED (Resistor is required)
- U2: Connect to dual triode vacuum tube

|||
|---|---|
|(J1) GND|(J1) IN|
|(J2) GND|(J2) +12V|
|(U2) GND|(U2) +12V|
|(U2) GND|(U2) K1|
|(U2) G2|(U2) G1|
|(U2) P2|(U2) P1|

### RV1, RV2, RV3, J3 and J4 (Top view)
- J3: Connect to output TRS jack (Sleeve and Tip)
- J4: Connect to output TRS jack (Ring)

|||
|---|---|
|(RV2) VOLUME IN|(J4) +12V|
|(RV2) VOLUME OUT|(J3) OUT|
|(RV2) GND|(J3) GND|
|(RV1) GAIN IN|(RV3) TONE IN|
|(RV1) GAIN OUT|(RV3) TONE OUT|
|(RV1) GND|(RV3) N.C.|

### J5
- J5: Connect to external voltage source for plate (Option)

## Jumpers
### JP1 Relay
If a short pin is connected to pins 1-2, the relay will always be energized as long as +12V is supplied to J4.  
If a footswitch is connected to pins 1-2, the relay will be energized only when the footswitch is on.  

### JP2 Plate Voltage
If a short pin is connected to pins 1-2, +12V supplied to J4 will be supplied to the plate.  
If a short pin is connected to pins 2-3 and an external voltage is supplied to J5, that voltage will be supplied to the plate.  

## BOM
|Ref|Val|
|---|---|
|K1|EA2-12NU|
|U1|LM386N-4|
|U2|12AU7|
|R1|1K|
|R2|100K|
|R3|470K|
|R4|47K|
|C1|223|
|C2|223|
|C3|223|
|C4|223|
|RV1|A250K|
|RV2|A250K|
|RV3|A250K|
