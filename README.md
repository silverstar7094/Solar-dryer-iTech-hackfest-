# Solar-dryer-iTech-hackfest-
<h2>A project we developed for iTech Hackfest Conducted at PSG</h2>
<h1>SOLAR DRYER</h1>
Solar dryers are devices that use solar energy to dry substances, especially food. Solar dryers use the heat from sun to remove the moisture content of food substances. There are two general types of solar dryers: Direct and indirect.

<h2>Problem Statement</h2>
We have chosen to develop a project using direct solar dryer concept.Generally a direct solar dryer uses 3-4 exhaust fans which consumes more power, as they run the whole time until the drying process is completed.
<h2>Objective</h2>
Our main objective is to reduce the power consumption, using an efficient method to dry the contents placed inside the container.
<h2>Innovation</h2>
We have found a effective way to maintain the required humidity and temperature inside the container, using a minimum number of exhaust fans. To reduce the power consumption, we have implemented louver mechanism as it controls the incoming  sunlight with low power consumption and so the exhaust fans do not run for a long period of time. Hence, the power consumed is reduced.

<h2>Requirements</h2>

<h3>Electronic Components</h3>

-->Arduino UNO R3

-->Exhaust Fan (CPU Cooler Fan)

-->Servo MG90S

-->DHT11 (Humidity and Temperature sensor)

<h3>Other Components</h3>

-->Container Box

-->Acrylic Board (3mm)

-->Jumper Cables

-->Louver Mechanism

<h2>Working</h2>

We have attached fins, to adjust the amount of sunlight entering the container. A servo motor will be used to control the fins(via louver mechanism).
At first, to increase the temperature inside the container, we decrease the humidity using an exhaust fan (i.e. Temperature is inversely proportional to Humidity). As the internals of the container is completely coated in black, for effective absorption of heat, and when the temperature specified is out of range, the fins close and isolate the container from any external heat exchanges. After the temperature decreases, the fins are opened to allow the sunlight to enter the container again, this process is repeated several times until the item placed in the container reaches an optimal condition (i.e. dried).
