# SF45B-Defense-Scanner
LightWare LiDAR SF45/B scanning microLiDAR.
The SF45/B microLiDAR is a very small **2D scanning LiDAR sensor** made by [LightWare LiDAR](https://lightwarelidar.com?utm_source=chatgpt.com) for:

* Robotics
* Drones (UAV)
* SLAM mapping
* Obstacle avoidance
* Autonomous navigation

![Image](https://images.openai.com/static-rsc-4/GLDeJ1BRxoqn8G7TdOgjLKzc7j70IHyKAhQ-o77jkfdc9GcqyZ7IAKu8BGQxYMuHcFvJuAVh7uSRHXPv9ghlY4430nxIRDKffmS2y3xE0aBVs7IPK2MDD8xjBC38z1vmd1jtMyG7DuPjbOOTy36xPX-O40isug_4Hvyq6JePOQuchaq3AtB7jGL-2ip9v3cZ?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/-ouwn5Fipz06BjX9NIbrDwCP-lsGM2iZtxjiJBGdB7rn8rQA42bTEHvUPLM6GYt7m0W-JhXi-nq7pUZd8w4Iu8GjuO1nfD4BizmvrokKtOtLcL92G9PZhKYg0VcdQxkvUjCEJzhlOkuTkSMNxTp5a6vg85a2jxCMkNQhoes6x0M7vKFKZeqmy94l4VmzzA-V?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/BAxavfngCAwDVxbNpH1GqGKYESeFeAyo6XrOw6j08BG_f4RlbV5KyF7eBiqC7VahtfumQO3ZWypthTcdlEb-Ey3rniELw9KhckreMaO7AZwAeX54a8x63_IGmvMxawUMrboMpNjz_F04kOkbWsdvfKUAofVgDfl3mu0rQ8WUpAJN4MCHUCpzUxiKePXlUOlC?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/k9tkk2iZ0pOjP7gA0e3O1AkpVX7LoTwt7pouuYHnfvuDTi46XMk4aKzomsoOUApOPEOSBKTZARiZiCvNZonnkUrrSrDDmRBSnCfXfLQESOwvT8JeKBsrAutVCWSdSB1X4EkE06qo5Cu1OzflVr1kax14Ae4MCjqoN0tZ_wvu1XxWUtmROUcfRzM9_MpXD4wj?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/tVOQmjgWiuKyqiSQnhjIOTS2g8osNC0ZCSn89GHhXV08Y3i5neTtDL8tQuY_M_76OazHjXuZCgjWYNeBu6-H-yNDmwAK4TUtkUUqJD5jYuim0OjH017DJ-JTS_Sa0G43A-atNxXL8YHUNsYpt_RHQsGpC6jpJNOM0wwLoNeRRx6xmyA-yGTF8ZJwHeI9gXn9?purpose=fullsize)

![Image](https://images.openai.com/static-rsc-4/mlWzoPKbM3R_j3AiOpUI7GfbliNs-2xePhzxEX-ir9lKybNvNNUZmMR13uPlEtg_Y5P66V0Hq90P3SKhDr7t3cAXA6rGNqZ8pqzmHaQ2jhJHiVhyCOWX-742cNKMDecEizVOGIBYagJj0aRSbXJxSAnn86hnl9t7jvKdgaZZ0CszuRRSgQpXl6fxFxVIgt02?purpose=fullsize)

### Main Specifications

| Feature    | Value                   |
| ---------- | ----------------------- |
| Scan Angle | Up to 320°              |
| Range      | 0.2m to 50m             |
| Weight     | ~58–59g                 |
| Scan Speed | Up to 5000 readings/sec |
| Interfaces | USB, UART, I2C          |
| Laser Type | 905nm Class 1M          |
| Use        | Indoor + Outdoor        |

([DigiKey][1])

### Works With

* Raspberry Pi
* Arduino
* Espressif Systems ESP32
* PX4
* ArduPilot
* ROS robotics systems

([LightWare LiDAR][2])

### What You Can Build

1. Autonomous robot
2. Drone obstacle avoidance
3. 2D room mapping
4. SLAM navigation
5. AI security rover
6. Warehouse robot
7. Smart terrain scanner

### Connection Example

SF45/B → Raspberry Pi 5

* TX → RX
* RX → TX
* GND → GND
* 5V → 5V USB/UART

You can read LiDAR data using:

* Python
* ROS
* C++
* Arduino IDE

### Example Python Use

```python
import serial

ser = serial.Serial('/dev/ttyUSB0', 115200)

while True:
    data = ser.readline()
    print(data)
```

### Official Resources

* [LightWare SF45/B Official Page](https://lightwarelidar.com/shop/sf45-b-50-m/?utm_source=chatgpt.com)
* [SF45/B Product Guide PDF](https://lightwarelidar.com/wp-content/uploads/2025/07/SF45B-Product-Guide-v3.pdf?utm_source=chatgpt.com)
* [DigiKey SF45/B Info](https://www.digikey.com/en/product-highlight/l/lightware-lidar/sf45-b-microlidar-distance-sensor?utm_source=chatgpt.com)

Price is usually around:

* $449 USD
* ₹45,000–₹50,000 in India

([DigiKey][1])

[1]: https://www.digikey.com/en/product-highlight/l/lightware-lidar/sf45-b-microlidar-distance-sensor?utm_source=chatgpt.com "SF45/B microLiDAR® Distance Sensor- LightWare| DigiKey"
[2]: https://lightwarelidar.com/shop/sf45-b-50-m/?utm_source=chatgpt.com "SF45/B (50 m) - World's Smallest & Lightest LiDAR"
