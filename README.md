## A Simple Server with Python Flask

When the server Pi2 receive the SENSOR messages, it adds an entry to the sensorlog file.

The P2 server provides a simple web interface showing a UCT logo and our names and 

The buttons for:

Sensor On: Turn on the sensors (i.e. send a SEND message to tell Pi1 to start sampling).

•Sensor Off : Turn off the sensors (i.e. send a SEND message to tell Pi1 to stop sampling).

•Status: use the CHECK message to see what the status of the Pi1 is (e.g. is it sampling,when did it last send a sample).

•Log Check: This function needs to print out the last 10 samples from the current run (or however many there are if less than 10 samples) to the screen.

•Log download: Allow user to download the current sensorlog file.

•Exit: This just exits the server program. It could show a screen exited.
