Archived.

Latest: https://github.com/ni/niveristand-instrument-addon-classes

Instrument-Custom-Device-Classes
========================

These classes are used in the Instrument Custom Device to handle the various instrument protocols and protection schemes over those protocols.

### LabVIEW Version ###

LabVIEW 2019.

### Built Availability ###

Users are allowed to build anything under Build Specifications in the source's LabVIEW project(s).  Pre-built versions are available upon request through NI Field Sales. 

### Quality, Limitations ###

IP has been tested by developer. It meets VeriStand addon coding best practices. It is currently used by various customers.

Addon does not support push messaging, meaning the instrument can't send unsolicited messages.

Addon is intended for slower rates, though the addon supports decimation so the NI VeriStand PCL can still be fast.

### Dependencies ###

NI VISA 19.0 or later
NI Serial 19.0 or later
OpenG LabVIEW Data Library 4.2.0.21 or later
OpenG Error Library 4.2.0.23 or later
NI STM 2.1.0.2 (ONLY)
NI AMC 3.3.0.20
NI GXML 1.4.2.8

### License ###

*This repository and any materials provided by NI therein are provided AS IS. NI DISCLAIMS ANY AND ALL LIABILITIES FOR AND MAKES NO WARRANTIES, EITHER EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION ANY WARRANTIES OF MERCHANTABILITY, FITNESS FOR  PARTICULAR PURPOSE, OR NON-INFRINGEMENT OF INTELLECTUAL PROPERTY. NI shall have no liability for any direct, indirect, incidental, punitive, special, or consequential damages for your use of the repository or any materials contained therein.*
