door handle
===========

A door handle has two sides.
assuming she(!) has the minimalist sensory data:
touch : boolean
doorState : boolean (open|close)
position : float (0.0 < pos <= 1.0)

// we can add many more to this list like: pressure on handle, light sensor, etc.

In the following situations:

* touch in then out
* touch out then in

can we teach her how to actuate: 

1. light inside
2. light out
3. door lock
4. water heater

e.g:
when door is touched on the outside and then the door opens - turn the light on.
door is touched on the inside and then closed - lock the door

the 'supervisor' of the learning scheme is the manual mode of the actuator (lightswitch, key-lock)