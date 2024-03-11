Welcome
------------------------------

Hi I'm Chris
(@nomad3k).  Please
feel free to ask me
anything.  I'm figuring
this stuff out as well. :)

Monday Mar 4th 2024
------------------------------

* Add LED to Arduino boad
  * PIN 2 = #5 (top)
  * GND   = #2 (bottom)
  * 3.3v  = #15 (bottom)

Objectives
----------

[X] Add LED + Resistor to the
    breadboard
[X] Connect the LED to Data
    Pin

What I learned
--------------

* Connections from Arduino are
  more fragile than expected.
  Soldering the board onto the
  pins will address this.
* Rust we to cast the Pin from
  it's native type.
* Arduino makes use of a
  private trait called
  'Sealed' which cannot be
  implemented outside the
  library, meaning public
  traits can only be
  implemented internally.
