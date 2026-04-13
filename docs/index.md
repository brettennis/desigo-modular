# Desigo Modular Operation

#### Contents

1. [Reading the main LEDs](#reading-the-main-leds)
2. [Using the main display](#using-the-main-display)
3. [Troubleshooting](#troubleshooting)

## Reading the main LEDs

POWER - glows steady green to indicate that the AC power is on; blinks when the System is on battery backup.

AUDIBLES - Audibles **ON** or Audibles **SILENCED** glows steady yellow to indicate the activation of horns/strobes.

PARTIAL SYSTEM DISABLED - glows steady yellow when any module/device is disabled or the system is in walktest.

CPU FAIL - glows steady yellow when a main processor failure occurs in the system. See the section on [Troubleshooting](#troubleshooting) to trigger a panel Hard Reset.

## Using the main display

When an event occurs in the system, the display enters the Alert or Firefighter’s mode automatically. Events are displayed in the following layout:

```md
|-------------------------------------------------------------------|
| Event Custom Message                                              |
|-------------------------------------------------------------------|
| Node Number | Time or Date | Device Type | Event Type | IN or OUT |
|-------------|--------------|-------------|------------|-----------|
```

Press the **More Info+** button to display a screen showing details relating to the selected event. Return to the previous screen by pressing **ESC**.

- _Note: Return to the main event list at any time by pressing **Menu** then **Alarm**._

#### Event types

The system can report four types of events: **Alarm**, **Supervisory**, **Security**, and **Trouble**. They are each shown on separate pages of Alert mode. Use the four soft keys above the display to navigate between them.

ALARM - The system has detected an active fire. Horns and strobes will activate in the building where the event is detected. A soft key below the display will appear labeled **Silence** to silence the horns.

SUPERVISORY - The system has detected an issue with a system it is monitoring. This includes the tampering of sprinkler valves and certain fire pump conditions.

SECURITY - This system is not set up to report security events.

TROUBLE - There is an issue with the fire system. Missing devices, ground faults, and battery failures are examples of trouble-causing events.

## Troubleshooting

The operator can trigger either a **Soft Reset** or a **Hard Reset** to reset the panel and display.

SOFT RESET - Press the soft key labeled **Reset** when on the main event screen. Any alarm event will temporarily be cleared, and then return if the device continues to report an alarm. Troubles labeled **OUT** will be cleared, while troubles labeled **IN** will return. This operation should take no more than 10 seconds.

HARD RESET - A hard reset can sometimes correct strange panel behavior. Open the inner door that houses the display. A small button labeled **RESET** can be found on the rear of the display, near the lower right corner. Press and hold this button for 3 to 5 seconds until a sustained beep is heard. A panel may take 1 to 2 minutes to reset, and up to 10 minutes to report all troubles accurately.