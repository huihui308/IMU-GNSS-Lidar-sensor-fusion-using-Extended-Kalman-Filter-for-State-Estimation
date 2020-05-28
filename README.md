# IMU-GNSS-Lidar-sensor-fusion-using-Extended-Kalman-Filter-for-State-Estimation

State estimation is so critical for autonomous vehicles (AV). It's the way the AV asks himself *"Where am I? How I'm moving?"* So, the *state* is an answer to where you are. That's the state estimation question. To answer it in the most likely right way, you need to use sensor data and even more, fuse the different sources of information to make stronger your believe about your current state. To fuse sensor data we used the Kalman Filter that has two basic steps, **Prediction** and **Correction** step. The *Prediction step* is based on the vehicle motion model that is feeded with IMU sensor data at a higher rate than data comes from GNSS (GPS) or Lidar sensor. Whilst the *Correction step* is executed every time a GPS or Lidar signal arrives to the vehicle, producing a *corrected* state.

Execute:
```
./es_ekf.py
```

![alt text](https://github.com/huihui308/IMU-GNSS-Lidar-sensor-fusion-using-Extended-Kalman-Filter-for-State-Estimation/blob/david/screenshots/ekf-sensor-fusion.png)
