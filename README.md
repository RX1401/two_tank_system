# two_tank_system
This project models an automated two-tank water management system using Arduino as the controller. It uses:

Ultrasonic sensors to measure water levels in both tanks.

An L298 motor driver to control a DC water pump or motor that moves water between the tanks.



🧠 Working Principle:
Water Level Detection:

Ultrasonic sensors (one per tank) measure the distance from the sensor to the water surface.

These distances are used to calculate the water level in each tank.

Control Logic (Arduino):

The Arduino continuously monitors water levels.

If the water in the first tank (Tank A) exceeds a threshold, and the second tank (Tank B) is not full, it activates the pump via the L298 motor driver.

Water Transfer:

The motor drives the water through the nozzle from Tank A to Tank B.

Once Tank B reaches its desired level or Tank A depletes below a limit, the pump stops.

🔄 Applications:
Smart irrigation systems

Water recycling and storage automation

Industrial process contro
