Welcome to the public repository of Volstora. 
This repo is the publically available information regarding system updates and changelogs. 

The system firmware is divided into EMS, system, and BMS software categories. 

## SYSTEM
### [System SYS-25.02] - 2025-06-26
This update enhances system monitoring and control capabilities with immediate response to conditions that prohibit system operation.

#### Added
- Additional sensors added to all systems to measure critical system environment parameters:
-   Temperature
-   Humidity
-   Carbon monoxide
- Realtime monitoring added for system environment parameters

#### Improved
- System cooling mechanism improved to react faster to temerature change requirements
- Improved system cooling mechanism to withstand upcoming summer heat

#### Fixed
- No changes

#### Security
- No Changes

### [System SYS-25.01] - 2025-05-17
This update enhances data security and compliance by migrating database infrastructure to European servers, ensuring alignment with European data protection standards.

#### Added
- Database infrastructure migrated to European Union servers
- Implemented GDPR-compliant data protection protocols
- Enhanced data residency and localization controls

#### Improved
- Data sovereignty measures
- Cross-border data transfer risk mitigation
- Regional security protocol implementations

#### Fixed
- No changes

#### Security
- Complete alignment with European Union data protection framework
- Improved data storage and access security
- Enhanced local data residency controls

## EMS
### [EMS openEMS TC-25.07.01] - 2025-07-02
This release focuses on improving system monitoring capabilities, enhancing local readability, and refining cell parameter calculations. Users can expect more accurate temperature readings and expanded system state visibility.

#### Added
- New Modbus API registers for enhanced local monitoring
- System state flags:
-   System Balanced
-   System Balancing
-   In operation

#### Improved
- Cell temperature readings calibrated to reduce reading errors

#### Fixed
- No changes

#### Security
- No changes

## BMS
### [BMS SSV2 V29] - 2024-06-20
This update focuses on improving Battery Management System (BMS) performance, diagnostic capabilities, and communication efficiency. We've optimized cell temperature management, enhanced system diagnostics, and resolved critical communication issues.

#### Added
- Refined balancing duty cycle to better manage cell temperatures
- Expanded debugging capabilities for more comprehensive error diagnosis
- Implemented additional operational condition verification checks

#### Improved
- Enhanced cell balancing strategy to maximize system efficiency
- Optimized data transmission through precise variable datatype management
- Streamlined system functions to reduce resource consumption

#### Fixed
- Resolved inter-BMS communication synchronization errors
- Corrected balancing hysteresis comparison inconsistencies

#### Security
- No changes

### [BMS SSV2 V28] - 2024-07-29
This battery firmware update will significantly improve battery balancing time and long-term stability by using both calibration and priority-based logic. Additionally, the battery charging and discharge parameters are adjusted for more discrete scenarios in terms of temperature, max cell voltage, and min cell voltage. 

#### Added
- Calibration function for factory calibration.
- Power-saving mode for long-term balancing.
- Additional power levels at boundary conditions of temperature and max/min cell voltage

#### Improved
- Balancing threshold for intercell and interpack balancing.
- Battery balancing speed by implenting priority-based logic. 
- Battery firmware start-up and loading speed.
- Battery temperature shutoff at high temperature threshold. 

#### Fixed
- Balancing thresholds below battery detection range.

#### Security
- No changes

Contact
For any questions or support, please contact us at support@volstora.com.
