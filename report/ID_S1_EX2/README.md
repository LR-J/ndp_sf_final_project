# ID_S1_EX2
## Point-Cloud Visualization
I have displayed views where the colour is indexed to altitude (blue for the lowest points - red for the highest points) and other views where the colour is indexed to the intensity of the reflected beam (black low intensity - white high intensity).
### Altitude
![plot](./images/id_s1_ex2_height_01.png)
Depending on the location of the vehicle in relation to the lidar, the front and one side of the vehicle or the rear and the other side can be captured.
The tyres are present.
In this scene, where the density of objects is high, there are many hidden areas.
![plot](./images/id_s1_ex2_height_02.png)
On the opposite side of the lidar, the vehicles are obviously not described at all.
![plot](./images/id_s1_ex2_height_03.png)

On the roofs, the clouds are not very dense. 
![plot](./images/id_s1_ex2_height_00.png)
The BEV highlights the poorly described areas.
### Intensity
![plot](./images/id_s1_ex2_int_00.png)
Images involving intensity yield similar conclusions.
![plot](./images/id_s1_ex2_int_01.png)
It should be noted that the intensity is sensitive to the nature of the surfaces (headlight lenses strongly reflect the laser) as well as the orientation of the surface.
At the corner of vehicles where the surfaces are normal to the laser beam, the reflected intensity is greater than on surfaces more tangential to the beam (side walls or roofs).
![plot](./images/id_s1_ex2_int_02.png)
![plot](./images/id_s1_ex2_int_03.png)
The headlights of the second vehicle on the left are clearly visible.
![plot](./images/id_s1_ex2_int_04.png)
![plot](./images/id_s1_ex2_int_05.png)
### Conclusion on stable elements
the front and rear bumpers, wheels, side walls, headlights seem to be the relatively stable objects.