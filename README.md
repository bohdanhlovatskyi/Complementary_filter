# IMU orientation check without sensor fusion

Low and High pass filters are implemented to check how bad is the gyro drift or the approach with solo-accelerometer+mag. 

Results:
- drift is quite terrible (though it is easy to see, how the Madgwick is based on gyro)
- acc + mag show a great result (even better than with filters) in greenhouse conditions (though in movement everything will be obviously really bad)
