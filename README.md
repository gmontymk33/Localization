# Localization
* Main task: "Self-localization of mobile robot with Kalman Filter"</br>


CODE DIVISION : </br>

Elena Kane i6289291 -  </br>
Nikolaos Ntantis i6273751 -  </br>
Ioannis Montesantos i6292068 -  </br>


TODO: </br>
motion move</br>
filter</br>
beacons</br>
sensors</br>
localization</br>
visuals in time steps</br>
add noise to movement</br>
add noise to sensors</br>

Visuals:
Ellipse =  show intermediate estimates of position and covariance</br>
Dotted line = estimated robot trajectory</br>
Solid line = actual robot trajectory</br>
Feature = black point</br>
Green line = between robot and feature, if feature is in sensor range</br>





• Point-based features </br>
• No walls, no collision with features</br>
• Omnidirectional sensor for feature detection</br>
• Limited sensor range</br>
• Bearing and distance estimate</br>
• Known correspondence</br>
• Velocity-based motion model (𝑢 = 𝑣, 𝜔 𝑇)</br>
• Control robot with key board (W=increment 𝑣, S=decrement 𝑣, A=decrement 𝜔 D=increment 𝜔, X=stop)</br>
• Track pose with Kalman Filter</br>
• Drive robot inside field with landmarks</br>
• Demonstrate what happens if no landmarks are visible to robot</br>
• Demonstrate what happens if 3 landmarks are visible to robot</br>
• Experiment with quality of sensors and motion control (noise)</br>
• Make sure to show proper visualization so we can see output of covariance matrices</br>
