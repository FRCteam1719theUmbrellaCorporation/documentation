# Documentation

This repo contains documentation for programming and hardware:  
These four changes originally took place on "Ringo Laptop":

Go to https://docs.yagsl.com/bringing-up-swerve/check-your-motors to find out what to do in the future

- On January 15th 2025, Ian Borden inverted the front right turn motor in the frontright.json for Ringo the robot
- On January 15th 2025, Ian Borden inverted the back right turn motor in the backright.json for Ringo the robot
- On January 15th 2025, Ian Borden inverted the back left turn motor in the backleft.json for Ringo the robot
- On January 15th 2025, Ian Borden inverted the front left turn motor in the frontleft.json for Ringo the robot

These changes were made using Shuffleboard by looking at the Raw Absolute Enconder and Raw Angle Encoder

For more info go to https://docs.yagsl.com/configuring-yagsl/when-to-invert

- Backleft Raw Absolute Encoder = 166.640625 or ~166.72
- Backright Raw Absolute Encoder = 252.0703125 or ~251.982
- Frontleft Raw Absolute Encoder = 191.162109375 or 191.25
- These three first values jumped between the two but the frontright encoder only had one value
- Frontright Raw Absolute Encoder = 318.8671875

These first of each of the four values were then inputed into the wheel jsons as the absoluteEncoderOffset

To create new jsons go to https://docs.yagsl.com/bringing-up-swerve/creating-your-first-configuration

In order to commit and then push, you most name the commit





Perry Sahnow on Jan 16 2025 changed a line in tuner constants for CTRE Swerve: public static final CANBus kCANBus = new CANBus...

Perry changed the type canbus from null to "Drivetrain"

* [Main page](https://github.com/FRCteam1719theUmbrellaCorporation/documentation/wiki)
