

 **Project : CELLNAV**

 To predict the position, velocity and acceleration of a ship, celestial navigation is used in addition to some other IMU measurement. The two measurements are fused 
 using the Extended Kalman Filter algorithm, in order to minimize noise and error in estimation. The Kalman Filter part is handled in the B_CELLNAV-kalman-tests.ipynb. There are other parts of the poject. 

 The celestial information is to be obtained from images of sky taken from the ship. The celestial co-ordinate then has to be converted to the Earth co-ordinate system. By comparing successive images the velocity, acceleration etc are to be found out.There will be large noise present in the derived result due to the noise present in the image and the detection process. 

 The Extended Kalman Filter algorithm provides us with a way of combining or fusing data from other sensors fixed within the body co-ordinate to calculate a more accurate and reliable estimate of position, velocity and angular orientation.

 
