# SV-V-LAB
| Req. ID | Description                                                                                                                                           | Priority |
| ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | -------- |
| **R1**  | The robot shall remain in the **IDLE** state when it is switched on and no delivery request has been received.                                        | **High** |
| **R2**  | When a valid delivery request is received while the robot is **IDLE**, the robot shall transition to **NAVIGATING** toward the requested destination. | **High** |
| **R3**  | While **NAVIGATING**, the robot shall continuously monitor its surroundings for obstacles.                                                            | **High** |
| **R4**  | When an obstacle is detected during navigation, the robot shall stop normal navigation and transition to **AVOIDING_OBSTACLE**.                       | **High** |
| **R5**  | After successfully avoiding an obstacle, the robot shall resume navigation toward the original destination.                                           | **High** |
| **R6**  | When the robot reaches the destination, it shall transition from **NAVIGATING** to **DELIVERING**.                                                    | **High** |
| **R7**  | The robot shall enter **DELIVERING** only after reaching the destination and shall not enter it directly from **IDLE** or **AVOIDING_OBSTACLE**.      | **High** |
| **R8**  | When the package is successfully delivered, the robot shall transition to **RETURNING** and begin traveling toward the warehouse.                     | **High** |
| **R9**  | If the battery level becomes critically low during navigation, the robot shall stop the current delivery journey and transition to **RETURNING**.     | **High** |
| **R10** | When the robot reaches the warehouse, it shall transition to **IDLE** and wait for a new delivery request.                                            | **High** |




