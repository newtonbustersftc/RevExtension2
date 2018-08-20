# RevExtensions2

The successor to REV Extensions

## What extra functionality does this add to the SDK?

 - Setting the LED color on the Hub
 - Setting the speed of the I2C buses on the Hub
 - Querying for total module current draw
 - Querying for servo bus current draw [ **broken:** REV firmware bug ]
 - Querying for GPIO bus current draw
 - Querying for I2C bus current draw
 - Querying for individual motor channel current draw
 - Reading the 5v monitor
 - Reading the 12v monitor
 - Queying for the internal temperature inside the Hub [ **broken:** unknown units ]
 - Query whether the Expansion Hub is in an over-temp condition
 - Query whether each individual motor H-bridge is over-temp
 - Query whether phone charging is enabled [ **broken:** REV firmware bug ]
 - Enable or disable phone charging
 - Setting servo pulse width directly in microseconds
 - Reading certain data in bulk from the Hub (can increase your control loop speed)
 - Query whether a motor has "lost counts" [ **broken:** no idea what this actually does ]
 - Query for which firmware version the Hub has installed
 - Query for which hardware revision the Hub is
