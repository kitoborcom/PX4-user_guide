# Standard Configuration

This section covers the common software configuration and calibration needed for most PX4 vehicles.

You must first [load firmware and select your vehicle frame/type](#firmware-vehicle-selection). Most other steps can be done out of order, except for [tuning](#tuning), which must be done last.

## Preconditions

Before starting you should [Download QGroundControl](http://qgroundcontrol.com/downloads/) and install it on your **desktop** computer. Then open the QGC application menu ("Q" icon in the top-left corner) and choose **Vehicle Setup** in the _Select Tool_ popup:

![QGC Main Menu Popup: highlighting Vehicle Setup](../../assets/qgc/setup/menu_setup.png)

## Configuration Steps

### Firmware/Vehicle Selection

- [Loading Firmware](../config/firmware.md)
- [Vehicle (Frame) Selection](../config/airframe.md)

### Motor/Actuator Setup

- [ESC Calibration](../advanced_config/esc_calibration.md)
- [Actuator Configuration and Testing](../config/actuators.md)

### Sensor Calibration

- [传感器方向](../config/flight_controller_orientation.md)
- [罗盘](../config/compass.md)
- [陀螺仪](../config/gyroscope.md)
- [加速度计 Accelerometer](../config/accelerometer.md)
- [Level Horizon](../config/level_horizon_calibration.md)
- [Airspeed](../config/airspeed.md) (Fixed-wing/VTOL only)

> **Note:** Setup for optional sensors and specific hardware is provided in [Flight Controller Peripherals](../peripherals/README.md).


### Manual Control Setup

Radio Control:

- [Radio Controller (RC) Setup](../config/radio.md)
- [Flight Mode Configuration](../config/flight_mode.md)

Joystick/GamePad:

- [操纵杆设置](../config/joystick.md)

### Safety Configuration

- [Battery/Power Module Setup](../config/battery.md)
- [Safety Configuration (Failsafes)](../config/safety.md)

### Tuning

- [Autotune](../config/autotune.md) (Recommended on vehicles and frames that support it)

## 视频教程

The video below shows most of the calibration process (it uses an older version of _QGroundControl_, but most of the process is unchanged).

@[youtube](https://youtu.be/91VGmdSlbo4)

## Support

If you need help with the configuration you can ask for help on the [QGroundControl Support forum](https://discuss.px4.io//c/qgroundcontrol/qgroundcontrol-usage).

## See Also

- [QGroundControl > Setup](https://docs.qgroundcontrol.com/master/en/SetupView/SetupView.html)
- [Flight Controller Peripherals](../peripherals/README.md) - Setup specific sensors, optional sensors, actuators, and so on.
- [Advanced Configuration](../advanced_config/README.md) - Factory/OEM calibration, configuring advanced features, less-common configuration.
- Vehicle-Centric Config/Tuning:

  - [Multicopter Config/Tuning](../config_mc/README.md)
  - [Helicopter Config/Tuning](../config_heli/README.md)
  - [Fixed Wing Config/Tuning](../config_fw/README.md)
  - [VTOL Config/Tuning](../config_vtol/README.md)
