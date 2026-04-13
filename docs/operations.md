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
