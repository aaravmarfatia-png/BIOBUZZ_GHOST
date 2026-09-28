BIOBUZZ FTC SDK COMPETITION CODE

This package is TeamCode source for the FTC SDK.

Hardware names required in Robot Configuration:
frontLeft
frontRight
backLeft
backRight
outtakeLeft
outtakeRight
axon1
axon2
axon3
axon4
servo25_1
servo25_2
servo25_3
imu
color
odoParallel
odoPerpendicular

Competition OpModes:
BIOBUZZ Competition TeleOp
BIOBUZZ Competition Auto

Diagnostics OpMode:
BIOBUZZ Hardware Diagnostics

Default driver controls:
Gamepad 1:
Left stick = field-centric translation
Right stick X = rotation
Right bumper = robot-centric override
Left bumper = slow mode
Start = zero heading

Gamepad 2:
A = home preset
B = intake preset
X = transfer preset
Y = score preset
Right trigger = outtake forward
Left trigger = outtake reverse
D-pad up = outtake on
D-pad down = outtake off

Before competition use:
1. Verify every configured hardware name exactly matches this file.
2. Confirm the Control Hub physical orientation and update the IMU parameters in RobotHardware if needed.
3. Verify left/right drive reversal on a stand.
4. Verify both outtake motor directions.
5. Calibrate every servo preset in RobotConfig.java on the assembled robot.
6. Measure and enter the real odometry pod offsets in RobotConfig.java.
7. Verify odometry forward and lateral signs.
8. Replace the sample autonomous routine with the actual season scoring sequence and field coordinates.
9. Test current draw, thermal behavior, hard stops, and emergency stop behavior.

The autonomous routine is intentionally conservative and generic because the CAD export does not contain the game-specific field path or calibrated mechanism positions.
