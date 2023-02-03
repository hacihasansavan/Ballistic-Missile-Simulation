# Ballistic-Missile-Simulation
Ballistic Missile Simulation in unity environment.

Demo Video:
https://www.youtube.com/watch?v=Raa_xLvVIa8

The codes will be uploaded soon...

In this project, a ballistic missile simulation physics will be implemented in unity environment. The physics system written from scratch.

Project content:
- 1-2-4 missile propulsion system and rocket orientation control
- The effect of the wind on the missile
- The effect of air density on the missile
- External control of the missile by phone
- Fuel tank location and filling (center of mass)
- Display systems (fuel, flight control, flight time, etc.)

General Structure of Ballistic Missiles:
Ballistic missiles usually consist of one, two or three parts. Each Compartment also contains its own engine and fuel. The first piece at the back pushes the missile until it runs out of fuel, and leaves the system when it runs out of fuel. Afterwards, the missile continues to be pushed by using the inner engine and fuel. Thus, when this compartment runs out of fuel, the missile goes into free slanting motion. It is aimed to hit the targeted point by following its trajectory.

![image](https://user-images.githubusercontent.com/57284868/216589197-f5608e92-a694-4fff-a8f4-8643db630066.png)

![image](https://user-images.githubusercontent.com/57284868/216589603-53aac27a-bf29-4395-8c83-a803044af17b.png)


Simulating the Wind:

Fw = 1/2.p.V^2.A
Fw : wind force at specific point   (N)
A  : surface area                   (m^2)
p  : density of air                 (kg/m^3)
v  : wind speed                     (m/s)
![image](https://user-images.githubusercontent.com/57284868/216589767-d77a8d06-ab8e-4151-b2c4-e92278232b7f.png)

![image](https://user-images.githubusercontent.com/57284868/216589897-aedcc427-8aaf-4946-a5ae-62d8d1ce98db.png)


Simulating Air Density![image](https://user-images.githubusercontent.com/57284868/216590613-652106f6-ce78-47ea-8b47-62a7142c7185.png)

Air density depends on these:
Density of dry air
-> p = Pa/(R*T)  
p : density of dry air
R : specific gas constant for dry air
T : Temperature
Pa : Pressure
![image](https://user-images.githubusercontent.com/57284868/216590633-d51bfab7-db93-445b-a0cb-5f794f2df06c.png)

Thrust System![image](https://user-images.githubusercontent.com/57284868/216590664-d90d3efd-e729-40dd-9eb7-b433fc0c3d82.png)

In the increasing of the missile speed, total mass, exhaust velocity, mass flow rate and also external forces like gravity, and air resistance play role.
![image](https://user-images.githubusercontent.com/57284868/216590691-d109841e-115f-47ea-b149-642219dc9f60.png)

Center of Mass
![image](https://user-images.githubusercontent.com/57284868/216590728-92fd9cc3-d536-487d-b162-641277fc0de9.png)

As we move the fuel tank down, the center of mass also goes down. And angular velocities and rotations applied according to this point
![image](https://user-images.githubusercontent.com/57284868/216590750-847ec0de-867c-464e-9970-63036979e7ca.png)

![image](https://user-images.githubusercontent.com/57284868/216590774-23a4e71b-8b04-44b5-a9cd-c70764d7e086.png)




Resources:

https://www.nasa.gov/sites/default/files/thumbnails/image/27420333805_6fd1876a46_o.jpg

https://www.quora.com/Could-an-ICBM-theoretically-be-able-to-be-launched-into-orbit

https://www.pngegg.com/en/png-dkpis/download
https://app.diagrams.net/

http://clipart-library.com/clip-art/warship-silhouette-5.htm

https://www.grc.nasa.gov/www/k-12/rocket/shortr.html

https://www.researchgate.net/	 
![image](https://user-images.githubusercontent.com/57284868/216590842-19fee4a7-4b9c-4e5c-b5d1-5f8e2ee6139e.png)

