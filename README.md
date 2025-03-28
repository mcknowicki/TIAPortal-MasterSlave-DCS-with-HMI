Authors: Maciej Nowicki and Bartosz Parszczyński

This system includes two Siemens PLC controllers connected into master/slave DCS, Sinamics V20 Inverter with a simple rotating engine wich imitates the work of the the conveyor belt connected to the master controller by the RS485 communication module
and a virtually simulated HMI panel.
It's main task is to set the amount of full work cycles of the engine (one cycle corresponds to the full conveyor belt's length) and do these work cycles. You can also set the speed and direction of rotation and in the case of malfunction you can
turn on the emergency mode wich turns the engine off and prevents it from starting again till you turn the emergency mode off.
