### 🚗 OpenSCENARIO Test Scenarios

* **🌫️ Low Visibility Pedestrian Crossing** (`low_visibility_pedestrian.xosc`)

  * A pedestrian crosses multiple lanes under **dense fog (20 m visual range)**.
  * The ego vehicle drives at \~**94 km/h**.
  * Tests rapid detection and emergency response under **low-visibility conditions**.

* **🚧 Construction Worker Crossing** (`construction_worker_crossing.xosc`)

  * A worker crosses a **coned work zone**.
  * The ego vehicle travels at \~**94 km/h**.
  * Evaluates **work zone handling, pedestrian detection, and obstacle negotiation** in constrained road geometry.

* **👷‍♂️ Multiple Construction Workers Crossing** (`construction_workers_crossing.xosc`)

  * Several workers cross a **roadwork zone with cones and obstacles**.
  * The ego vehicle drives at \~**94 km/h**.
  * Tests **simultaneous pedestrian detection, obstacle avoidance, and safe navigation** in a visually complex work zone.

* **🏍️ Motorcycle Lane Split** (`motorcycle_lane_split.xosc`)

  * A motorcycle performs a **lane-splitting maneuver** through dense highway traffic.
  * Eventually merges into the ego vehicle’s lane.
  * Tests **awareness of fast, narrow vehicles** and handling of sudden lateral movements.

* **🚛 Static Trucks Encounter** (`static_sumo.xosc`)

  * Ego vehicle encounters **multiple static trucks blocking different lanes**.
  * Must decelerate, change lanes twice, and park safely.
  * Tests **evasive maneuver planning, lane change handling, and controlled stopping**.

* **🚚 Static Trailer Encounter** (`static_trailer.xosc`)

  * Ego approaches a **static truck trailer blocking its lane** at \~**144 km/h**.
  * Requires braking and a lane change to avoid collision.
  * Evaluates **obstacle detection, deceleration, and lateral maneuvering**.
