# dronecode_sdk::Camera::CaptureInfo Struct Reference
`#include: camera.h`

----


[Information](structdronecode__sdk_1_1_camera_1_1_information.md) about a picture just captured. 


## Data Structures


struct [EulerAngle](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_euler_angle.md)

struct [Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md)

struct [Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md)

## Data Fields


struct [dronecode_sdk::Camera::CaptureInfo::Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md) [position](#structdronecode__sdk_1_1_camera_1_1_capture_info_1ac820f2cd756043a9623f26055ca096a0)  - [Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md) of drone/camera when image was captured.

struct [dronecode_sdk::Camera::CaptureInfo::Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md) [attitude_quaternion](#structdronecode__sdk_1_1_camera_1_1_capture_info_1a87e2b8236a6804af88c074004dfe3ce2)  - [Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md) of camera orientation.

struct [dronecode_sdk::Camera::CaptureInfo::EulerAngle](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_euler_angle.md) [attitude_euler_angle](#structdronecode__sdk_1_1_camera_1_1_capture_info_1a304055fe45a5770f48208288045dba7f)  - Euler Angle of camera orientation.

uint64_t [time_utc_us](#structdronecode__sdk_1_1_camera_1_1_capture_info_1a48bd4b59b8378f9b350fec07d5b67aa8)  - Timestamp in UTC (since UNIX epoch) in microseconds.

bool [success](#structdronecode__sdk_1_1_camera_1_1_capture_info_1a8c8d385b09707b1c2b516ccf5a10aaae)  - True if capture was successful.

int [index](#structdronecode__sdk_1_1_camera_1_1_capture_info_1a037b736dd3ba7fa3efbe620a2c93b1aa)  - Zero-based index of this image since armed.

std::string [file_url](#structdronecode__sdk_1_1_camera_1_1_capture_info_1a04bc92de25c0a9235343ebc1fb0687b9)  -


## Field Documentation


### position {#structdronecode__sdk_1_1_camera_1_1_capture_info_1ac820f2cd756043a9623f26055ca096a0}

```cpp
struct dronecode_sdk::Camera::CaptureInfo::Position  dronecode_sdk::Camera::CaptureInfo::position
```


[Position](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_position.md) of drone/camera when image was captured.


### attitude_quaternion {#structdronecode__sdk_1_1_camera_1_1_capture_info_1a87e2b8236a6804af88c074004dfe3ce2}

```cpp
struct dronecode_sdk::Camera::CaptureInfo::Quaternion  dronecode_sdk::Camera::CaptureInfo::attitude_quaternion
```


[Quaternion](structdronecode__sdk_1_1_camera_1_1_capture_info_1_1_quaternion.md) of camera orientation.


### attitude_euler_angle {#structdronecode__sdk_1_1_camera_1_1_capture_info_1a304055fe45a5770f48208288045dba7f}

```cpp
struct dronecode_sdk::Camera::CaptureInfo::EulerAngle  dronecode_sdk::Camera::CaptureInfo::attitude_euler_angle
```


Euler Angle of camera orientation.


### time_utc_us {#structdronecode__sdk_1_1_camera_1_1_capture_info_1a48bd4b59b8378f9b350fec07d5b67aa8}

```cpp
uint64_t dronecode_sdk::Camera::CaptureInfo::time_utc_us
```


Timestamp in UTC (since UNIX epoch) in microseconds.


### success {#structdronecode__sdk_1_1_camera_1_1_capture_info_1a8c8d385b09707b1c2b516ccf5a10aaae}

```cpp
bool dronecode_sdk::Camera::CaptureInfo::success
```


True if capture was successful.


### index {#structdronecode__sdk_1_1_camera_1_1_capture_info_1a037b736dd3ba7fa3efbe620a2c93b1aa}

```cpp
int dronecode_sdk::Camera::CaptureInfo::index
```


Zero-based index of this image since armed.


### file_url {#structdronecode__sdk_1_1_camera_1_1_capture_info_1a04bc92de25c0a9235343ebc1fb0687b9}

```cpp
std::string dronecode_sdk::Camera::CaptureInfo::file_url
```


Download URL for captured image.