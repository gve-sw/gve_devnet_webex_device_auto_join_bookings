# GVE DevNet Webex Device Auto Join Bookings
Macro to enable Webex device to automatically join meetings that are offered via a booking when the Booking Start 
event is received.  
This allows for Webex Devices to be encased in such a way that none of the user controls are accesible, but when the device 
as configured in a calendar is included in a booking for a meeting or, if a personal device, if the person that owns the device is in a Webex Space when someone initiates a meeting, the device will automatically join that meeting when it starts.

## Contacts
* Gerardo Chaves (gchaves@cisco.com)


## Solution Components
* Webex Collaboration Devices
* Javascript
* xAPI

## Requirements
1. Cisco Webex device that supports xAPI commands and macros
3. Firmware CE9 or newer

## Installation/Configuration

Load and activate the Javascript code included in the the **auto_join_bookins.js** file in this repository into a new Macro in the Macro editor of the Cisco Webex Device you want to start auto-joining booked meetings.   
 
If you are unfamiliar with Cisco Room device macros, this is a good article to get started:
https://help.webex.com/en-us/np8b6m6/Use-of-Macros-with-Room-and-Desk-Devices-and-Webex-Boards




## Usage

Once the macro is running, any time a meeting starts where the device has been added in an integrated calendar, or if a personal mode device and the user belongs to Space where a meeting is started manually by any Space member, the device will automatically join the meeting. 

For scheduled meetings, the device will disconnect when the meeting ends. 

## Additional Information
##### XAPI

Documentation for the XAPI can be found in the [Command References overview](https://www.cisco.com/c/en/us/support/collaboration-endpoints/telepresence-quick-set-series/products-command-reference-list.html).




# Screenshots



### LICENSE

Provided under Cisco Sample Code License, for details see [LICENSE](LICENSE.md)

### CODE_OF_CONDUCT

Our code of conduct is available [here](CODE_OF_CONDUCT.md)

### CONTRIBUTING

See our contributing guidelines [here](CONTRIBUTING.md)

#### DISCLAIMER:
<b>Please note:</b> This script is meant for demo purposes only. All tools/ scripts in this repo are released for use "AS IS" without any warranties of any kind, including, but not limited to their installation, use, or performance. Any use of these scripts and tools is at your own risk. There is no guarantee that they have been through thorough testing in a comparable environment and we are not responsible for any damage or data loss incurred with their use.
You are responsible for reviewing and testing any scripts you run thoroughly before use in any non-testing environment.