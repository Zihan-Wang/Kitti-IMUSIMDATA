# Kitti-IMUSIMDATA

+ This repo includes simulated data by using ground truth of Kitti dataset

## files format

- $(Kitti-name).txt

This includes ground truth  (timestamp, tx, ty, tz, qx, qy, qz, qw)

- feats.csv

including all feature points pose and sequence number  (Number, tx, ty, tz)

- imumeas.csv

including IMU measurements  (Timestamp, Ax, Ay, Az, Wx, Wy, Wz)

- imupose.csv

including estimated poses by IMU propagation  (timestamp, tx, ty, tz, qx, qy, qz, qw)
