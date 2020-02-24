Source: https://www.thingiverse.com/thing:3397997


* Print the calibration model matching Your nozzle size with flowrate set to 100%. Extrusion width must be set to nozzle diameter.

* Using calipers, measure width of a few top layers. Do it in the middle of each wall. I recommend measuring from 2 to 5 last layers. But be consequent! Make all measurements in the same way.

* Take the average value from measuring all walls.

* Now using the following formula calculate new flowrate value:

A = Expected dimension. If You are using 0.4 nozzle, expected dimension should be twice as large - 0.8 mm.

B = Measured dimension. Value from point 3.

F = Current Flowrate.

(A / B) * F = Your new flowrate value

* Print the model again but now sliced with new flowrate value.

* Measure the model again. If average value from measuring all walls is equal to expected dimension You are done. If it's not then calculate flowrate again using current value and repeat the process untill achieving expected resaults.
