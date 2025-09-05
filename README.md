
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
