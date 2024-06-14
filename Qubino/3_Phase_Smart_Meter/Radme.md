# Qubino 3-Phase Smart Meter changelog

## [50.06 - 02.02] - [2021-01-07]
- fixed output check when set is sent for endpoint 5
- corrected measuring chip version to dispaly 02.02
- fixed supervision & switch reports when any relay enabled and command are encapsulated CRC16 encapsulation
- fixed reporting on time interval for other values (parameter 43)
- other minor fixes and improvements

## [50.00 - 02.02] - [2020-11-13]
- removed S0 seccuirty command class
- updated PN from ZMNHXD1 H1S1P2 to ZMNHXD1 H1S5P2  
- other minor fixes and improvements

## [41.20 - 02.02] - [2020-08-25]
- fixed meter report when receivin meter get command CRC16 encapsulated
- changed version format

## [04.11 - 02.02] - [2020-04-24]
- fixed reports from ep5
- fixed bug when both endpoints controled the same relay
- fixed association group command list get report for endpoint 5 and 6
- fixed basic and switch binary version report when any relay is enabled
- fixed LED behaviour when relay are ON and OFF
- fixed relay reports when only one is enabled
- changed minimum allowed value of parameters 42 and 43 Time reporting interval from 600 seconds to 30 seconds
- other minor fixes and improvements

## [01.00 - 02.02]
Original certified version