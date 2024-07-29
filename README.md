Welcome to the public repository of Volstora. 
This repo is the publically available information regarding system updates and changelogs. 

The system firmware is divided into EMS, system, and BMS software categories. 

### [BMS SSV2 2.2.1] - 2024-07-29
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
