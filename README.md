# RTIMULib-Arduino - a versatile 9-dof and 10-dof IMU library for the Arduino

## Please note that this project is no longer active and is of historical interest only.


Simply added MPU9255 support.(By modifying codes on MPU9250)...
Maybe helpful to someone in need... 

##Usage:
	1.Connecting:
		3.3v-VCC
		GND-GND
		SDA-SDA
		SCL-SCL
	2.Add library to your ArduinoIDE:
		Please copy all files and folders of "libraries" into your ArduinoIDE installation directory Arduino/libraries .
	3.Run mag_cal:
		Build and upload "ArduinoMagCal/ArduinoMagCal.ino".
		You will get output stop as you almost finishing the calibration. Then send "s" to your Arduino (with no comma), which provides an output like "Mag cal data saved for device XXX".
	4.Test output:
		Build and upload "ArduinoIMU10/ArduinoIMU10.ino" or "ArduinoIMU/ArduinoIMU.ino" to see output.

##Attention:
	Watch out "#define  SERIAL_PORT_SPEED  115200"! It should be same as settings in ArduinoIDE.Or you will get everything fucking up...