### Reverse-Guidance ###

The Reverse Guidance is the first block of the Autonomous Truck Project building by Hexagon Mining.

The follow link talk about this key step of Autonomous toward the Full Autonomous Haulage: [Reverse Guidance - Hexagon Publication](http://hexagonmining.com/blog/2017/10/13/reverse-guidance-key-step-to-autonomous-haulage?utm_source=hootsuite&utm_medium=linkedin&utm_campaign)

<img src="http://hexagonmining.com/-/media/Images/Hexagon/Hexagon%20Core/Hexagon%20Mining/Blog/2017/October/reverse_guidance.ashx?la=en&hash=CA5F87E54FBA7720497BAA113E2D984563649371" alt="Reverse-Guidance" width="800px">

How Reverse Guidance works:

Reverse Guidance system calculates the optimum reversing path for a truck to follow when backing into a shovel pit to be loaded, or when backing to a hopper to unload.

* When an equipped truck enters a shovel pit or dumping area, the low-precision GNSS receivers will change to a high-precision mode that allows for centimeter accuracy.
* When the transmission is shifted to reverse a path will be planned to a spot location, avoiding mapped objects. 
* Using this path, an optimal steering angle will be calculated and the operator will be prompted to adjust steering angle to this value through light bars attached to the mirrors and through an audible prompt. 
* As the operator reverses the truck, the truck's position and orientation will be compared to the calculated path. The operator will receive prompts if corrections are necessary.
* Distance to the stopping point will be indicated through audible prompts.
* When the spot is reached, a continuous audible prompt is issued. 

The follow link shows a presentation of the reverse guidance product at Las Vegas conference in 2017: https://www.youtube.com/watch?v=V7-0Jj_6yyA


### Embedded Core Modules ###
* Machine-To-Machine communication - C++;
* Local Path Planner - C++;
* Motion Controller - C++;
* Behavior - C++;
* Peripherals and Extended modules - Python;
* Infrastructure and Deploy - Shell and Python 

### Frameworks and Technologies ###
* Robot Operating System (ROS) - http://www.ros.org/
* POCO Framework - https://pocoproject.org/
* QT - https://www.qt.io/
* MachinaIO - https://macchina.io/
* MQTT - http://mqtt.org/
* ActiveMQ - http://activemq.apache.org/
* ZeroMQ - http://zeromq.org/
* Data Distribution Service (DDS) - http://portals.omg.org/dds/
* Ubuntu (Linux) 14.04 - http://releases.ubuntu.com/14.04/
* Yocto - https://www.yoctoproject.org/

### Contact ###
* [ildefonso.neto@hexagonmining.com](mailto:ildefonso.neto@hexagonmining.com)
* [ildefonso.neto.f@gmail.com](mailto:ildefonso.neto.f@gmail.com)

### Patent Published ###

There is a Patent published with Reverse Guidance assistance maneuver. This patent show the main people worked on that.

<img src="https://user-images.githubusercontent.com/19958282/32137070-ddaf8960-bbf7-11e7-98e5-489a56c3e56f.png" alt="Patent" width="800px">
