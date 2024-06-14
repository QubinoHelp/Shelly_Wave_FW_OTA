# Qubino Smart Plug 16A

## [41.11] - [2022/10/12]
- Fixed bug kWh not reported after meter reset

## [41.10] - [2021/01/31]
- Fixed bug causing to stop count at 429 kWh
- Fixed bug not sending switch binary report after turning off output in connection with conf. param. 73
- Fixed bug not sending unsolicited notification report after clearing overload detected alarm
- reworked the logic for calculating, storing and reporting kWh value
- lower time interval to store kWh value from 30 to 5 minutes
- updated PN  
- removed 2 old unused parameters
- other minor fixes and improvements

## [40.00] - [2020/10/05]
- removed S0 command class
- changed Part Number
- other minor fixes and improvements

## [03.00] - [2018/10/15]
- initial commit