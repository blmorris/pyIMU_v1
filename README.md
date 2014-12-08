pyskin-IMU
==========

Directory pyIMU contains an IMU skin for the pyboard, providing the MPU9150 accelerometer / gyro / magnetometer and the BMP180 barometric altimeter.

The eagle library pyIMU-03.lbr provides all components and symbols used in this board and schematic.

UPDATE: pyIMU-GPS contains an updated version of the original pyIMU board with a fully integrated GPS receiver module and interface circuitry for monitoring current draw and voltage on a Li-polymer battery pack.

Several device packages have been modified from the originals provided by Sparkfun and the standard Eagle libraries; this is to eliminate design rule check errors and ensure that there is soldermask between the pins on the fine-pitch (0.5mm) components.

The project uses the SSC-EAGLE-2Lyr_v1.0.0.3.dru design rule file; this is a design rule set for 2-layer boards provided by Sunstone Circuits: http://www.sunstone.com/news-resources/cad-tools/eagle

The current project should not generate any errors when run against this DRU file.

