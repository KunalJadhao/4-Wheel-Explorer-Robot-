
# 🛠️ My 4-Wheel Autonomous Robot URDF

A simple **4-wheeled differential drive robot** model created using **URDF** (Unified Robot Description Format) for ROS/ROS2 simulations.  
This robot is designed for use in **RViz** and **Gazebo** for visualization, navigation experiments, and robotics learning.

---

## 📷 Preview

![image_alt](https://github.com/KunalJadhao/4-Wheel-Autonomous-Robot-/blob/main/Screenshot%20from%202025-08-08%2010-49-23.png)
![image_alt](https://github.com/KunalJadhao/4-Wheel-Autonomous-Robot-/blob/main/Screenshot%20from%202025-08-08%2010-49-08.png?raw=true)
![image_alt](https://github.com/KunalJadhao/4-Wheel-Autonomous-Robot-/blob/main/Screenshot%20from%202025-08-08%2010-49-16.png?raw=true)
![image_alt]([https://github.com/KunalJadhao/4-Wheel-Autonomous-Robot-/blob/main/Screenshot%20from%202025-08-08%2010-49-23.png](https://github.com/KunalJadhao/4-Wheel-Autonomous-Robot-/blob/51c3403f5f4b3ef3c7964144e13ed681dbb8b7ba/Screenshot%20from%202025-08-08%2010-51-18.png))

---

## 📂 Project Structure

```

urdf_tutorial/
│
├── urdf/
│   └── my_robot.urdf        # The main URDF file for the robot

## ⚙️ Robot Features

* ✅ 4-wheeled differential drive layout
* ✅ Continuous joints for wheel rotation
* ✅ Realistic wheel positions for simulation
* ✅ Uses `base_footprint` for proper localization in ROS
* ✅ Materials and colors for better visualization

## 🛠️ Customization

You can modify:

* **Wheel size** → change `radius` and `length` in `<cylinder>`
* **Base size** → edit `<box size="x y z"/>`
* **Colors** → change `<material>` RGBA values
* **Wheel positions** → adjust `xyz` in `<origin>`

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).
