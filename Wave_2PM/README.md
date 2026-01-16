**version [16.05] - [2025-01-16]**
* Fixed Multichannel Association on EP 2

**version [16.04] - [2025-11-27]**
* Detached mode SW2 fixed
* External switches exclusion disabled

**version [16.02] - [2025-10-17]**
**Important note**
Before proceeding, we recommend restoring Parameters No. 36–40 (Power report on change – percentage and Minimum time between reports) to their default values.
If these parameters are set too low, it may cause issues during the reinterview process, which is required after the update to ensure the configuration is displayed correctly.

* SDK with fixed dead node issue
* Added detached mode and kWh precision set to 2 decimal points
* Parameter 117 (reboot parameter)
* Watt reports when NO/NC parameter is active
* Other minor improvements

**version [15.00] - [2025-07-15]**

* Fix switch binary report when powered with DC
* Fix Endpoint 2 report state change on singlechannle association
* Fix supervision report for root command
* Removed parameters no. 91, 92, 93, 94 from the FW
* Other minor improvements

**Important note firmware version 12.04**
*After receiving several reports from users that the device began turning off the output randomly after the firmware update, we decided to withdraw the update until we can identify and correct the issue. For users experiencing this random shut-off, the recommended solution is to downgrade the firmware to version 10.30 (EU) or 10.35 (AU).*

We appreciate all of the custoemrs tha brought the issue to our attention, and we are pleased to provide an update on our research. We value all bug reports, as they play a crucial role in helping us identify and address issues, ultimately leading to the development of better devices.

**Root Cause Analysis and Temporary Solution for Shelly Wave 2 PM Firmware Issue**
Following an extensive investigation, we have successfully replicated the issue causing the Shelly Wave 2 PM to intermittently turn off the outputs. Our analysis reveals that the problem occurs when the gateway routes commands through the 2PM device. Notably, this issue is not attributed to our code implementation on the device, but rather a defect in the SDK (Software Development Kit) version 4.4.1, which is used in firmware version 12.04.

**Current Workaround**
As a temporary solution, we recommend downgrading the affected devices to firmware version 10.30 (10.35), which does not utilize the problematic SDK version. This downgrade should mitigate the issue until a permanent fix is available.

**Next Steps**
We are currently awaiting a resolution from Silicon Labs, the SDK provider, and will provide an update once a permanent solution is implemented. We appreciate your patience and understanding in this matter.

**version [12.04] - [2024-06-07] (version removed possible bug - version under investigation)**

* Fixed Meter reports, Associations and Binary Switch
* Add root control and reports of endpoints
* Improved over-current and over-voltage protection
* Other minor improvements

**version [10.35] - [2024-03-28]**

* Optimised temperature conversion table
* Other minor improvements

**version [10.30] - [2023-12-13]**

* Removed delay from input detection to output response.

**version [10.27] - [2023-06-05]**

* initial firmware release
