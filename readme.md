# Koch v1.1 Robotic Arm Calibration & Control with LeRobot Framework

## Project Overview
Construct and use the Koch v1.1 Robot with the LeRobot AI Robotics Framework

## Goals
- Install and configure the LeRobot framework
- Calibrate Koch v1.1 robotic arms
- Run basic control scripts (positioning, motion sequences)
- Use AI to teach the arms to pick up and sort small objects

## Technologies Used
- Python 3.10
- LeRobot Framework (custom robotics middleware)
- Ubuntu 22.04 (recommended)
- Git & GitHub
- Koch v1.1 hardware (USB/Serial)

## Issues I ran into & Fixes
- I spent quite a few hours trying to solve dependancy issues I experienced on my laptop running Fedora Linux, I found the best environment to run lerobot in to minimize dependancy issues was an Ubuntu Virtual Machine.
- Occasionally the arms will drift from their initial calibration. To resolve this you must delete all your calibration files in your ~/.cache and rebuild the files.
- We ran into some issues with our 3D printed components, we found the best way to resolve these was to print a couple different versions until we got a perfect part.

## Resources
- https://github.com/jess-moss/koch-v1-1
- https://github.com/huggingface/lerobot
- https://www.youtube.com/watch?v=8nQIg9BwwTk&list=PLo2EIpI_JMQu5zrDHe4NchRyumF2ynaUN
