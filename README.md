# IoTExamples
Examples with XAML and C# for W10 IoT

<b>RGB Led</b>

At this moment you can set the GPIO Pins to high and low, this is an example on how to change the color using the current GpioPin class.

<a href="http://expediteapps.com/blog/usando-un-rgb-led-en-una-app-w10-iot/">Post (spanish)</a>

<img src="http://expediteapps.com/blog/wp-content/uploads/2015/05/sheet.png" />

<b>Basic Thermometer</b>

Using a capacitor and two GPIOS you can measure the changes of the resistance of a thermistor by measuring the time that takes the capacitor to charge or discharge.

<a href="http://expediteapps.com/blog/temperature-with-gpios-in-windows10iot-with-rpi2/">Post </a>

<img src="http://expediteapps.com/blog/wp-content/uploads/2015/05/thermistor.jpg" />

<b>Fan Motor</b>

<a href="http://expediteapps.com/blog/l9110-fan-motor-with-rpi2-with-windows-10-iot/">Post </a>

<img src="http://expediteapps.com/blog/wp-content/uploads/2015/05/fanmotor.jpg" />

In this case you can connect directly to the raspberry Pi 2 this L9110 (controller chip) Fan Motor and make the motor forward, reverse and stop just by setting GPIOs high and low

I have improved the code to implement Hardware HVVH pattern, in order to make a base to implement scalable hardware views

<b>Potentiometer and Moisture Sensor with SPI</b>

<a href="http://expediteapps.com/blog/sensingworldw10iot/">Post </a>

<img src="http://expediteapps.com/blog/wp-content/uploads/2015/06/SPI.jpg" />

Now the Hardware implementation has the SPI device and is really quick and easy to add to your project and keep that internally.

<b>Remote Relays</b>

<a href="http://expediteapps.com/blog/lucesremotas/">Post (spanish)</a>

<img src="http://expediteapps.com/blog/wp-content/uploads/2015/06/relaycircuit.png" />

In this case, I have implemented a REST Server, a REST client, and all the logic to switch bulbs with a relay and its driver.