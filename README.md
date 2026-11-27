# Alive Controller

A VEX IQ controller in your browser — for **any VEX IQ (2nd gen) robot**.

- 3D VEX IQ controller and Brain you can click, drag and pick up
- Keyboard driving (WASD + arrows), left arcade / split arcade / tank, power = Bluetooth on/off, lock-controller view
- Connects to the robot over Web Bluetooth (Chrome or Edge), with the 4-digit pairing code
- Direction test fixes reversed or swapped wheels without editing code (remembered per robot)
- Follow me: the robot drives to your camera and stops 10 inches away
- 3D Level Up field (from VEX's official field CAD) with a drivable 3D robot: skeleton (drivetrain only) or full (catapult, differential, air tanks), real hitboxes, and with Brain program v8 it moves with the real robot (wheel encoders + gyro), auto-tunes itself and holds a straight line
- Real match mode (3-2-1, 1:00, scoring on L1–L4 by the Level Up rules), Load Zones with a Loader, a 60 s Skills auton (3 L4 + 10 L3), driver view at the end of the field
- Match timers from YouTube to pick from: Ben Lipper, Tournament Manager, Star Wars (Chewbotca), Epic Bros; can stop the robot when it ends

## Use it with your robot

1. Open the site in Chrome or Edge and go to **Robot log → Show Brain program → Copy**.
2. Paste it into a new VEXcode IQ **Python** project. At the top, set `ROBOT_NAME` and your motor ports
   (`LEFT_PORTS`, `RIGHT_PORTS`, optional `INTAKE_PORT` / `SHOOTER_PORT`).
3. Download it to the Brain, run it, quit VEXcode, then press **Power on & connect** and pick your robot.
   Not in the list? Use **Show all Bluetooth devices**.

Fan-made. Not affiliated with VEX Robotics or Innovation First. 3D models converted from VEX's public CAD files.
Built with React, three.js and React Bits components. Made by 77718W Winterbots.
