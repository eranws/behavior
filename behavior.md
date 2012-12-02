Door Handle
=========== 

A door handle has two sides.
assuming she(!) has the minimalist sensory data:
    
    touch (yes|no)
    doorState (open|close)
    position (0..1)

<script>
/*
DoorHandle{
isTouch : boolean //(yes|no)
doorState : boolean (open|close)
position : float // (0..1)
// we can add more sensors to this list like: pressure on handle, light sensor, etc.
*/
</script>

In the following situations:

* touch in then out
* touch out then in

<script>
/*
this can be like a state machine, or time based
*/
</script>


Can we teach her how to actuate: 

1. light inside
2. light outside
3. door lock
4. water heater

example
--
when handle is touched on the **outside** and then the door **opens** - *turns on* the light<br/>
when handle is touched on the **inside** and then the door **closed** - *locks* door

learning
--
the 'supervisor' of the learning scheme is the manual mode of the actuator (lightswitch, key-lock)

--
Click [here](http://prose.io/#eranws/behavior/edit/gh-pages/behavior.md) to edit
