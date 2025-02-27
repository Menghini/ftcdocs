Sensors
=========

.. note:: 
   As per :ref:`Game Manual Part 1<manuals/game_manuals/game_manuals:game manuals>` 
   a UVC Webcam is not considered a sensor.

Listed below are a couple examples of common sensors in FTC. This is not
intended to limit or extend in anyway the scope of sensors as established in
``<RE12>``. While the FTC SDK supports many sensors not all are natively
supported.

Examples
----------

Distance Sensor (Ultrasonic)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. grid:: 1 2 2 2 
   :gutter: 2

   .. grid-item-card::
      :class-header: sd-bg-dark font-weight-bold sd-text-white
      :class-body: sd-text-left body
      
      MB1242

      ^^^

      .. figure:: images/MB1242.jpg
         :align: center
         :alt: MB1242
         :width: 50%

      +++

      MB1242

   .. grid-item-card::
      :class-header: sd-bg-dark font-weight-bold sd-text-white
      :class-body: sd-text-left body

      RCWL-1601

      ^^^

      .. figure:: images/RCWL-1601.jpg
         :align: center
         :alt: RCWL-1601
         :width: 50%

      +++

      RCWL-1601


An Ultrasonic Distance Sensor is a device that is able to measure the distance
between an object and the sensor.  It does this by sending out a sound wave and
measuring the time it takes for the wave to travel to the object and back.
Using this and the speed of sound the distance can be calculated.

Distance Sensor (Optical)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. grid:: 1 2 2 2 
   :gutter: 2

   .. grid-item-card::
      :class-header: sd-bg-dark font-weight-bold sd-text-white
      :class-body: sd-text-left body
      
      REV-31-1505

      ^^^

      .. figure:: images/REV-31-1505.png
         :align: center
         :alt: REV-31-1505
         :width: 50%

      +++

      REV-31-1505

An Optical Distance Sensor is a device that is able to measure the distance
between an object and the sensor. It does this by sending out a light beam and
measuring the time it takes for the beam to travel to the object and back.
Using this time and the known speed of light the distance can be calculated. Be
mindful the way the object in question interacts with light can change the
accuracy of the distance measurement. A transparent object like field panels
will often provide innacurate measurements.

Color Sensor
~~~~~~~~~~~~~~

.. grid:: 1 2 2 2 
   :gutter: 2

   .. grid-item-card::
      :class-header: sd-bg-dark font-weight-bold sd-text-white
      :class-body: sd-text-left body
      
      REV-31-1557

      ^^^

      .. figure:: images/REV-31-1557.png
         :align: center
         :alt: REV-31-1557
         :width: 50%

      +++

      REV-31-1557

   .. grid-item-card::
      :class-header: sd-bg-dark font-weight-bold sd-text-white
      :class-body: sd-text-left body
      
      MR 45-2018

      ^^^

      .. figure:: images/45-2018.png
         :align: center
         :alt: MR 45-2018
         :width: 50%

      +++

      MR 45-2018

A color sensor is a digital output device that is able to measure the color of
an object. Most color sensors require the object in question to be relatively
close to the sensor. 

Touch Sensor
~~~~~~~~~~~~~~

.. grid:: 1 2 2 2 
   :gutter: 2

   .. grid-item-card::
      :class-header: sd-bg-dark font-weight-bold sd-text-white
      :class-body: sd-text-left body
      
      REV-31-1425

      ^^^

      .. figure:: images/REV-31-1425.png
         :align: center
         :alt: REV-31-1425
         :width: 25%

      +++

      REV-31-1425

A touch sensor is a digital output device that detects the activation of a
button. This can be used as a limit switch, a way to limit the range of motion
of a mechanism. Such a device would typically use the digital port.


Magnetic Limit Switch
~~~~~~~~~~~~~~~~~~~~~~~~

.. grid:: 1 2 2 2 
   :gutter: 2

   .. grid-item-card::
      :class-header: sd-bg-dark font-weight-bold sd-text-white
      :class-body: sd-text-left body
      
      REV-31-1462

      ^^^

      .. figure:: images/REV-31-1462.png
         :align: center
         :alt: REV-31-1462
         :width: 25%

      +++

      REV-31-1462

A Magnetic Limit Switch is used to detect the presence of a magnet in near
proximity. This is commonly used to limit the range of movement of a mechanism
that would cause damage if it went beyond said limit. This is done by placing a
magnet on said mechanism which would cause the Limit Switch to activate. It is
important to note that as a digital device this will only send out a boolean
output and not a range. For measureing the strength of a magnetic field take a
look at a magnetometer.

IMU
~~~~~

.. grid:: 1 2 2 2 
   :gutter: 2

   .. grid-item-card::
      :class-header: sd-bg-dark font-weight-bold sd-text-white
      :class-body: sd-text-left body
      
      NAV X2 Micro

      ^^^

      .. figure:: images/navx2.png
         :align: center
         :alt: NAV X2 Micro
         :width: 50%

      +++

      NAV X2 Micro

   .. grid-item-card::
      :class-header: sd-bg-dark font-weight-bold sd-text-white
      :class-body: sd-text-left body
      
      BNO055

      ^^^

      .. figure:: images/BNO055.jpg
         :align: center
         :alt: BNO055
         :width: 50%

      +++

      BNO055


An Interial Measurement Unit (IMU) is sensor that is a combination of a
Gyroscope, Accelerometer, and Magnetometer. A Gyroscope is device that reports
the `angular orientation <https://en.wikipedia.org/wiki/Orientation_(geometry)>`_ 
of an object in 3 dimensions. An Accelerometer is a device that reports the
acceleration of an object in 3 dimensions. Acceleration can be thought of as
the rate of change of speed at any given instance. A Magnetometer is a device
that measures the strength of magnetic fields in 3 axis.  This can be used as a
compass to gain the orientation of a robot relative to the poles of the Earth,
an absolute measurement.

Potentiometer
~~~~~~~~~~~~~~~

.. grid:: 1 2 2 2 
   :gutter: 2

   .. grid-item-card::
      :class-header: sd-bg-dark font-weight-bold sd-text-white
      :class-body: sd-text-left body
      
      REV-31-1155

      ^^^

      .. figure:: images/REV-31-1155.png
         :align: center
         :alt: REV-31-1155
         :width: 50%

      +++

      REV-31-1155

   .. grid-item-card::
      :class-header: sd-bg-dark font-weight-bold sd-text-white
      :class-body: sd-text-left body
      
      50k Ohm Potentiometer

      ^^^

      .. figure:: images/BBG-770.jpg
         :align: center
         :width: 50%
         :alt: BBG-770

      +++

      50k Ohm Potentiometer

A Potentiometer is a device that changes the output voltage based upon the
degree to which the adjuster is turned. It is often used in FTC as a form of
measuring the absolute orientation of an axle. The manner in which the output
voltage change is subject to change based on the Potentiometer that is used.
Such a device is typically attatched via the analog port of the REV Hub.


Additional Resources
---------------------

 - :ref:`Analog Port Overview <control_hard_compon/rc_components/hub/ports/ch-ports:analog ports>`
 - :ref:`Digital Port Overview <control_hard_compon/rc_components/hub/ports/ch-ports:digital ports>`
 - :ref:`I2C Port Overview <control_hard_compon/rc_components/hub/ports/ch-ports:i2c ports>`
