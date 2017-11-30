# gpslock
Determine the current GPS location of a computer, periodically check that the location 
has not changed and ensure that the USB GPS dongle is still attached.

If the USB dongle is removed or the computer's GPS location shows it has moved beyond
a certain distance (given potential normal variations in GPS readings) then perform
a system shutdown.
