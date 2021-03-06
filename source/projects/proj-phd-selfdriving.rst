Self Driving Car Hardware/Firmware
====================================
As a part of self-driving car project I designed required PCB, firmware and software to interface a computer with the vehicle.
first project was a funded by Toyota and I designed hardware/firmware required to read all vehicle sensors (encoders, IMU, state-machine states) and also power all electronics/computers/cameras/Velodyne from a 12v secondary car battery.
here are a couple of photos from finished platform

.. figure:: ../media/toyota0.jpg
    :width: 400
    :align: center

    self-driving car with Velodyne Lidar and cameras on roof

.. figure:: ../media/toyota1.jpg
    :width: 400
    :align: center

    my custom designed compute system capable of controlling all sensors and powering the whole system

.. figure:: ../media/toyota2.jpg
    :width: 400
    :align: center

    compute platform in trunk


Later I joint `Zoox <https://zoox.com/>`_ as an intern to help them with their self-driving taxi project, I worked on different parts of the project during my 1.5 month internship but most exciting one was when I came up with a hack to use the steering assist motor to steer the vehicle with computer.

while ispecting the steering system I realized that there is a closed loop control over steering torque and by breaking feedback from steering torque sensor and placing a microcontroller which can generate a differential analog voltage I could report a high torque signal to ECU (as if the driver is trying to steer rapidly) and then ECU would apply a high torque to steering assist motor. by creating a PID loop over this system I was able to steer the car without any mechanical modifications to the car.


In this video I made a quick experiemt to fool the vehicle's ECU. I glued two potentiometers head to head where one was turning clock-wise and other ani-clock-wise and they would generate the differential signal whichh was expected by ECU.

.. raw:: html

    <iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/Mx9RusXMRkU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>