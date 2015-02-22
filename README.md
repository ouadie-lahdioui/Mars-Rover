Mars Rover Kata
===============

The Mars rover is programmed to drive around Mars. Its programming is very simple. The commands are the following:
<dl>
  <dt>s</dt>
  <dd>drive in a straight line</dd>
  <dt>r</dt>
  <dd>turn right</dd>
  <dt>l</dt>
  <dd>turn left</dd>
</dl>

Note that the Mars rover always land at the <code>X</code> and starts by facing east.

The Mars rover can send a 2D string representation of its path back to Mission Control. The following character are
used with the following meanings:
<dl>
  <dt>X</dt>
  <dd>where the Mars rover landed</dd>
  <dt>*</dt>
  <dd>current position of the Mars rover</dd>
  <dt>-</dt>
  <dd>path in the west-east direction</dd>
  <dt>|</dt>
  <dd>path in the north-south direction</dd>
  <dt>+</dt>
  <dd>a place where the Mars rover turned or a crossroad</dd>
  <dt>S</dt>
  <dd>a place where a sample was taken</dd>
</dl>
