# Summary

* [Introduction](README.md)
  * [FAQ](getting_started/faq.md)
<!-- * [Quick Start](getting_started/README.md) -->
* [iOS/Swift](http://dronecode-sdk-swift.s3.eu-central-1.amazonaws.com/docs/master/index.html)
* [Python](https://github.com/mavlink/MAVSDK-Python#mavsdk-python)
* [C++ (MAVSDK Core)](cpp/README.md)
  * [Guide](guide/README.md)
    * [Usage/Paradigms](guide/general_usage.md)
    * [Connecting to Systems (Vehicles)](guide/connections.md)
    * [Managing Systems](guide/using_plugins.md)
    * [System Information](guide/system_information.md)
    * [Telemetry](guide/telemetry.md)
    * [Actions - Take Off, Arm, ...](guide/taking_off_landing.md)
    * [Missions](guide/missions.md)
    * [Offboard Control](guide/offboard.md)
    * [Follow Me](guide/follow_me.md)
    * [VTOL Support](guide/vtol.md)
    * [Building C++ Apps](guide/toolchain.md)
    * [SDK Extensions](guide/sdk_extensions.md)
  * [Examples](examples/README.md)
    * [Takeoff and Land](examples/takeoff_and_land.md)
    * [Fly Mission](examples/fly_mission.md)
    * [Fly QGC Plan Mission](examples/fly_mission_qgc_plan.md)
    * [Offboard Mode - Velocity Control](examples/offboard_velocity.md)
    * [Follow Me Mode](examples/follow_me.md)
    * [VTOL Transitions](examples/transition_vtol_fixed_wing.md)
  * [API Reference](api_reference/README.md)
    * [class Action](api_reference/classmavsdk_1_1_action.md)
    * [class Calibration](api_reference/classmavsdk_1_1_calibration.md)
      * [struct ProgressData](api_reference/structmavsdk_1_1_calibration_1_1_progress_data.md)
    * [class Camera](api_reference/classmavsdk_1_1_camera.md)
      * [struct CaptureInfo](api_reference/structmavsdk_1_1_camera_1_1_capture_info.md)
        * [struct EulerAngle](api_reference/structmavsdk_1_1_camera_1_1_capture_info_1_1_euler_angle.md)
        * [struct Position](api_reference/structmavsdk_1_1_camera_1_1_capture_info_1_1_position.md)
        * [struct Quaternion](api_reference/structmavsdk_1_1_camera_1_1_capture_info_1_1_quaternion.md)
      * [struct Information](api_reference/structmavsdk_1_1_camera_1_1_information.md)
      * [struct Option](api_reference/structmavsdk_1_1_camera_1_1_option.md)
      * [struct Setting](api_reference/structmavsdk_1_1_camera_1_1_setting.md)
      * [struct SettingOptions](api_reference/structmavsdk_1_1_camera_1_1_setting_options.md)
      * [struct Status](api_reference/structmavsdk_1_1_camera_1_1_status.md)
      * [struct VideoStreamInfo](api_reference/structmavsdk_1_1_camera_1_1_video_stream_info.md)
      * [struct VideoStreamSettings](api_reference/structmavsdk_1_1_camera_1_1_video_stream_settings.md)
    * [class FollowMe](api_reference/classmavsdk_1_1_follow_me.md)
      * [struct Config](api_reference/structmavsdk_1_1_follow_me_1_1_config.md)
      * [struct TargetLocation ](api_reference/structmavsdk_1_1_follow_me_1_1_target_location.md)
    * [class Geofence](api_reference/classmavsdk_1_1_geofence.md)
      * [struct Polygon](api_reference/structmavsdk_1_1_geofence_1_1_polygon.md)
        * [struct Point](api_reference/structmavsdk_1_1_geofence_1_1_polygon_1_1_point.md)
    * [class geometry::CoordinateTransformation](api_reference/classmavsdk_1_1geometry_1_1_coordinate_transformation.md)
      * [struct GlobalCoordinate](api_reference/structmavsdk_1_1geometry_1_1_coordinate_transformation_1_1_global_coordinate.md)
      * [struct LocalCoordinate](api_reference/structmavsdk_1_1geometry_1_1_coordinate_transformation_1_1_local_coordinate.md)
    * [class Gimbal](api_reference/classmavsdk_1_1_gimbal.md)
    * [class Info](api_reference/classmavsdk_1_1_info.md)
      * [struct Identification](api_reference/structmavsdk_1_1_info_1_1_identification.md)
      * [struct Product](api_reference/structmavsdk_1_1_info_1_1_product.md)
      * [struct Version](api_reference/structmavsdk_1_1_info_1_1_version.md)
    * [class LogFiles](api_reference/classmavsdk_1_1_log_files.md)
      * [struct Entry](api_reference/structmavsdk_1_1_log_files_1_1_entry.md)
    * [class MavlinkFTP](api_reference/classmavsdk_1_1_mavlink_f_t_p.md)
    * [class MavlinkPassthrough](/api_reference/classmavsdk_1_1_mavlink_passthrough.md)
    * [class Mavsdk](api_reference/classmavsdk_1_1_mavsdk.md)
    * [class Mission](api_reference/classmavsdk_1_1_mission.md)
    * [class MissionItem](api_reference/classmavsdk_1_1_mission_item.md)
    * [class MissionRaw](api_reference/classmavsdk_1_1_mission_raw.md)
      * [struct MavlinkMissionItemInt](api_reference/structmavsdk_1_1_mission_raw_1_1_mavlink_mission_item_int.md)
    * [class Mocap](api_reference/classmavsdk_1_1_mocap.md)
      * [struct AngleBody](api_reference/structmavsdk_1_1_mocap_1_1_angle_body.md)
      * [struct AngularVelocityBody](api_reference/structmavsdk_1_1_mocap_1_1_angular_velocity_body.md)
      * [struct AttitudePositionMocap](api_reference/structmavsdk_1_1_mocap_1_1_attitude_position_mocap.md)
      * [struct Odometry](api_reference/structmavsdk_1_1_mocap_1_1_odometry.md)
      * [struct PositionBody](api_reference/structmavsdk_1_1_mocap_1_1_position_body.md)
      * [struct Quaternion](api_reference/structmavsdk_1_1_mocap_1_1_quaternion.md)
      * [struct SpeedBody](api_reference/structmavsdk_1_1_mocap_1_1_speed_body.md)
      * [struct VisionPositionEstimate](api_reference/structmavsdk_1_1_mocap_1_1_vision_position_estimate.md)
    * [class Offboard](api_reference/classmavsdk_1_1_offboard.md)
      * [struct ActuatorControl](api_reference/structmavsdk_1_1_offboard_1_1_actuator_control.md)
        * [struct Group](api_reference/structmavsdk_1_1_offboard_1_1_actuator_control_1_1_group.md)
      * [struct Attitude](api_reference/structmavsdk_1_1_offboard_1_1_attitude.md)
      * [struct AltitudeRate](api_reference/structmavsdk_1_1_offboard_1_1_attitude_rate.md)
      * [struct PositionNEDYaw](api_reference/structmavsdk_1_1_offboard_1_1_position_n_e_d_yaw.md)
      * [struct VelocityBodyYawspeed](api_reference/structmavsdk_1_1_offboard_1_1_velocity_body_yawspeed.md)
      * [struct VelocityNEDYaw](api_reference/structmavsdk_1_1_offboard_1_1_velocity_n_e_d_yaw.md)
    * [class Param](api_reference/classmavsdk_1_1_param.md)
    * [class Shell](api_reference/classmavsdk_1_1_shell.md)
      * [struct ShellMessage](api_reference/structmavsdk_1_1_shell_1_1_shell_message.md)
    * [class System](api_reference/classmavsdk_1_1_system.md)
    * [class Telemetry](api_reference/classmavsdk_1_1_telemetry.md)
      * [struct AccelerationNED](api_reference/structmavsdk_1_1_telemetry_1_1_acceleration_n_e_d.md)
      * [struct ActuatorControlTarget](api_reference/structmavsdk_1_1_telemetry_1_1_actuator_control_target.md)
      * [struct ActuatorOutputStatus](api_reference/structmavsdk_1_1_telemetry_1_1_actuator_output_status.md)
      * [struct AngularVelocityBody](api_reference/structmavsdk_1_1_telemetry_1_1_angular_velocity_body.md)
      * [struct AngularVelocityNED](api_reference/structmavsdk_1_1_telemetry_1_1_angular_velocity_n_e_d.md)
      * [struct Battery](api_reference/structmavsdk_1_1_telemetry_1_1_battery.md)
      * [struct EulerAngle](api_reference/structmavsdk_1_1_telemetry_1_1_euler_angle.md)
      * [struct GPSInfo](api_reference/structmavsdk_1_1_telemetry_1_1_g_p_s_info.md)
      * [struct GroundSpeedNED](api_reference/structmavsdk_1_1_telemetry_1_1_ground_speed_n_e_d.md)
      * [struct Health](api_reference/structmavsdk_1_1_telemetry_1_1_health.md)
      * [struct IMUReadingNED](api_reference/structmavsdk_1_1_telemetry_1_1_i_m_u_reading_n_e_d.md)
      * [struct MagneticFieldNED](api_reference/structmavsdk_1_1_telemetry_1_1_magnetic_field_n_e_d.md)
      * [struct Odometry](api_reference/structmavsdk_1_1_telemetry_1_1_odometry.md)
      * [struct Position](api_reference/structmavsdk_1_1_telemetry_1_1_position.md)
      * [struct PositionBody](api_reference/structmavsdk_1_1_telemetry_1_1_position_body.md)
      * [struct PositionNED](api_reference/structmavsdk_1_1_telemetry_1_1_position_n_e_d.md)
      * [struct PositionVelocityNED](api_reference/structmavsdk_1_1_telemetry_1_1_position_velocity_n_e_d.md)
      * [struct VelocityNED](api_reference/structmavsdk_1_1_telemetry_1_1_velocity_n_e_d.md)
      * [struct Quaternion](api_reference/structmavsdk_1_1_telemetry_1_1_quaternion.md)
      * [struct RCStatus](api_reference/structmavsdk_1_1_telemetry_1_1_r_c_status.md)
      * [struct SpeedBody](api_reference/structmavsdk_1_1_telemetry_1_1_speed_body.md)
      * [struct StatusText](api_reference/structmavsdk_1_1_telemetry_1_1_status_text.md)
    * [class Tune](api_reference/classmavsdk_1_1_tune.md)
    * [namespace mavsdk (globals)](api_reference/namespacemavsdk.md)
    
  * [Contributing](contributing/README.md)
    * [Building Source](contributing/build.md)
    * [Testing](contributing/test.md)
    * [Writing Plugins](contributing/plugins.md)
    * [Coding Style](contributing/code_style.md)
    * [Plugin/Test Logging](contributing/dev_logging.md)
    * [Documentation](contributing/documentation.md)
* [Releases](releases/README.md)

## Dronecode Shortcuts

* [PX4 Developer Guide](https://dev.px4.io/en/)
* [PX4 User Guide](https://docs.px4.io/en/)
* [QGroundControl User Guide](https://docs.qgroundcontrol.com/en/)
* [QGroundControl Developer Guide](https://dev.qgroundcontrol.com/en/)
* [MAVLink Guide](https://mavlink.io/en/)
* [Dronecode Camera Manager](https://camera-manager.dronecode.org/en/)
