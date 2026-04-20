# More Operations

The Maintenance menu allows an operator to disarm output activations and individual devices for testing and maintenance purposes. A complete history log of events is accessible using the History menu.

#### Contents
1. [Disarm outputs](#disarm-outputs)
2. [Disarm devices](#disarm-devices)
3. [Access event history](#access-event-history)

## Disarm outputs

Disarm functions allow the disabling of horns/strobes, AHU shutdowns, elevator recall, or elevator shunt trip activation. A panel's disarm functions are local only, and will not affect other buildings.

- Navigate to disarm functions by pressing **Menu** then **Function Keys**
- Select function then press **Execute**
    - _Note: Disarming or Arming an output will cause a new trouble event._
- Navigate to main event list: **Menu** then **Alarm**

## Disarm devices

The Maintenance menu allows the disabling of individual smoke detectors, manual pull stations, or monitor points. A global panel can target devices in any building.

- Navigate to Maintenance menu by pressing **Menu** then **Maint**
- Navigate to device using &#128316;, &#128317;, **More Info+**, or **ESC**
    - _Note: Press **Geographic View** to navigate building zones or **Physical View** to navigate device loops. The current view is indicated at the upper left of the screen._
- Press **Control** with device highlighted
- Enter password: `12345678` then **Done**
- Select **Disarm** or **Arm** then **Execute**
    - _Note: Disarming or Arming a device will cause a new trouble event and light the LED labeled **Partial System Disabled**._
- Navigate to main event list: **Menu** then **Alarm**

## Access event history

A panel's history log is stored through panel resets and power failure.

- Navigate to Report menu by pressing **Menu** then **Report**
- Navigate to node/building using &#128316;, &#128317;, **More Info+**, or **ESC**
    - _Note: Press **Physical View** to access history. **Geographic View** can not be used to access history._
- Press **History** with node/building highlighted
- **Settings** then **Start Time** to filter based on timestamp
- **View** to display event history
- Scroll event history using &#128316; and &#128317;
- **Select** to toggle between timestamp, message, and description
- Navigate to main event list: **Menu** then **Alarm**

## Walktest mode

Walktest is an alternative method of disarming outputs for the purpose of testing devices. Outputs such as horns/strobes or HVAC shutdown relays can be disabled on the scale of an entire building, or a specific geographic area, if geographic groups have been programmed. At this site, geographic groups have been programmed only for the Administration building.

#### Walktest vs. Disarm functions

Disarm functions (see above: [Disarm outputs](#disarm-outputs)) achieve similar results to activating walktest mode for a building, with some key differences:
- Walktest mode will automatically time-out after 4 hours, unless manually extended at the panel. Disarm functions, however, will remain active until functions are rearmed. 
- Activation of a walktested device will not report to remote annunciators installed in master control rooms. When a disarm function is enabled, all devices will report to annunciators as normal.
- While disarm functions can target a building, walktest mode can target a specific geographic area. For example, the Warehouse area of the Administration building can be put in walktest, leaving devices in Segregation to report alarms as normal.
- An area in walktest mode can be configured to activate audibles for five seconds upon activation of a device. This allows a user to test functionality of devices in the field without a person watching the panel for messages.

#### Initiating a walktest

- Navigate to Maintenance menu by pressing **Menu** then **Maint**
- Navigate to area using &#128316;, &#128317;, **More Info+**, or **ESC**
    - _Note: Press **Geographic View** to navigate geographic groups or **Physical View** to navigate device loops. The current view is indicated at the upper left of the screen._
- Press **Walktest** with area highlighted
- Enter password: `12345678` then **Done**
- Press **Settings** to configure walktest bell options
    - **No Bells**: walktested devices will not activate horns/strobes
    - **All Bells**: walktested devices will activate horns/strobes for five seconds
    - **Group Bells**: this site is not configured to use Group Bells
- Press **Enable** to initiate the walktest
    - _Note: Initiating a walktest will cause new trouble events and light the LED labeled **Partial System Disabled**._
- Navigate to main event list: **Menu** then **Alarm**

Devices activated in walktested areas will report to the panel for 30 seconds, and be stored in a report indefinitely. This report can be retrieved at any time by navigating to **Menu**, **Report**, **Status**, **Walktest**.

A walktest will remain active for 4 hours. A user can extend the walktest at any time by pressing **Menu**, **Maint**, **Walktest**, and **Extend**. The walktest can be canceled by pressing **Disable**.

Five minutes before the end of the walktest, a 15-second audible activation occurs. Forty-five seconds before the end of the Walktest, a 45-second audible activation occurs. If **No Bells** has been configured, only strobes will be activated. 
    - _Note: Any devices still in alarm at the time the walktest expires will cause the system to go into alarm as normal. Do not test devices after the five-minute warning._

When the Walktest is completed, acknowledge the _WALKTEST ACTIVATED_ trouble and reset the panel.