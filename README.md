<div align="center">
  <img src="header_sce.png" width="100%">
</div>

# LunaSats-UCB-Team

Our team is passionate about aerospace engineering research, and our goal is to strengthen our scientific research skills and thus, in the near future, seek to empower the next phase of space exploration of our country, Bolivia. The team believe that promoting space science and technology to the Bolivian community is essential to achieve our goal. In order to achieve that, we want to show the younger students that they themselves can aspire to develop technology that will take us as far as space.


## Rocket landing via Sequential Convex Programming

Rocket landing is one of the most exiting and challenging topics in spacecraft aerodynamics, specially if you are an enthusiastic student. Imagine, if this is a complex task in earth, the level increases even more outside it. In order to achieve a safe landing, we need to take in consideration the terminal position, velocity, and attitude constrains. And, when talking about attitude, we need to make a mention of atmospheric drag and disturbance torques, like magnetic torque or solar pressure force, among others. The previously mentioned variables can be estimated with considerable precision for the earth atmosphere, but what happens if we want to land our rocket in the exterior space? For example, in the moon or Mars.

Computing guidance onboard the spacecraft is a proper strategy in order to accomplish the required constrains, and successfully land the rocket.  But, is commonly known, as the mission complexity increases, most guidance problems are required to achieve the optimal solution. The application of numerical optimization methods is attracting researchers attention, and the convex optimization is one of those attractive methods that can theoretically guarantee the convergence and efficiency for aerospace operations.

<div align="center">
  <img src="equations.png" width="61%">
</div>

Model Predictive Control could be considered for rocket landing due to its unique capability with respect to constrains satisfaction, optimized performance and adaptability for model uncertainty. Also, we can mention its advantages of handling constraints and optimization performance simultaneously via repeatedly solving an optimal control problem.

<div align="center">
  <img src="landing_python.png" width="61%">
</div>

<div align="center">
  <img src="video_landing.gif" width="61%">
</div>

As most of the research teams cannot afford to land real rockets to test their models and assumptions, we must opt to perform simulations, like the one which can be visualized above. But, although these simulations can show an approximate behavior to the real one of the landing process, disturbance variables of the landing location, like the moon or Mars, are required to obtain a robust control system simulation. In the case of the above visualized simulation, those parameters can be incorporated to obtain better and more robust results.


## Rover exploration

In order to evaluate the performance of the Rocket landing and rover, certain variables need to be measured and correspond to Lunasat sensors??? that include:
- Temperature sensor: The temperature is the most important variable to measure because of its influence in the atmospheric drag disturbance, since temperature is directly relationated with density and so with this disturbance. Furthermore, the temperature can be interpreted as a danger parameter since all embedded components in telemetry systems work optimally in a specific range of temperatures. Also, it is a critical factor in the entire structure of the rover because the temperature coefficient of materials can determine how all parts of the vehicle will dilate or contract.
- Accelerometer: Acceleration is useful for determining the velocity of the spacecraft since it is an important variable to control it. And also for the rover because we are able to compute the travel time and the force that is required to overcome obstacles with slope.
- Magnetometer: The magnetic field can conditionate the control performance of the spacecraft since one of the most influential disturbances is the magnetic disturbance due to the interaction of the Moon???s magnetic field and the magnetic dipole of the spacecraft. By measuring the magnetic field we can determine the maximum perturbation from the external magnetic field,and so estimate and simulate the spacecraft  performance. Additionally, this variable can affect the telemetry system of the vehicle since the magnetic field is useful for orientation approaches.
- Thermopile: Due to the limited battery available, this component can wake-up battery only when something is detected. For example, if there were a kind of obstacle near, a braking system can be activated saving an important amount of energy. The detection of nearby obstacles is an important issue, since the rover structure is made of metals such as steel and aluminum, and if the vehicle collides, a phenomenon called cold welding can occur.Where, due to the absence of oxygen, pieces of metal can fuse, without the need for a conventional welding technique. Even tought the Von Misses stress analysis shows a clear resistance (for example in wheels), the impact can cause pieces of metal to come together and fuse.
<div align="center">
  <img src="wheel.png" width="50%">
</div>


<div align="center">
  <img src="final_final.JPG" width="70%">
</div>
<div align="center">
  <img src="DSC_6477.JPG" width="70%"> 
</div>
