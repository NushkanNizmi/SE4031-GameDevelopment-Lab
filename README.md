# 🧪 Lab 01 – Manual VR Setup in URP (Without VR Template)

Duration: 2 Hours  
Project Type: Separate project (NOT used for future labs)

---

## Objective

Learn how to manually configure Virtual Reality in Unity using URP (Universal Render Pipeline), OpenXR, and XR Interaction Toolkit without using the built-in VR template.

---

## Learning Outcomes

By the end of this lab, you will be able to:

- Create a URP project for VR  
- Install and configure required XR packages  
- Enable OpenXR manually  
- Create an XR Rig (XR Origin)  
- Configure basic teleport locomotion  
- Run a simple VR scene  

---

## Software Requirements

- Unity Hub  
- Unity 2022.3 LTS  
- Windows PC  
- VR Headset (optional but recommended): Meta Quest (Link), HTC Vive, Valve Index  

---

## Project Name

Lab01_ManualVR_URP

---

## Step 1 – Create URP Project

1. Open Unity Hub  
2. Click New Project  
3. Select template: 3D (URP)  
4. Set project name as: Lab01_ManualVR_URP  
5. Click Create  

Wait until Unity finishes loading the project.

---

## Step 2 – Install Required Packages

1. Open Window → Package Manager  
2. Change the top-left dropdown to Unity Registry  
3. Install the following packages one by one:

- XR Plug-in Management  
- OpenXR Plugin  
- XR Interaction Toolkit  
- Input System  

4. If Unity asks to restart for Input System, click Restart.

Checkpoint: All four packages must show as Installed.

---

## Step 3 – Enable OpenXR

1. Open Edit → Project Settings → XR Plug-in Management  
2. Under PC, Mac & Linux Standalone, enable OpenXR  

Then configure controller profiles:

1. Go to Project Settings → OpenXR  
2. Under Interaction Profiles, click + and add one profile:

- Oculus Touch Controller Profile (Quest)  
- OR Vive Controller Profile  
- OR Index Controller Profile  

Checkpoint: Your controller profile should appear in the list.

---

## Step 4 – Create XR Rig (XR Origin)

1. In Hierarchy, right click → XR → XR Origin (Action-based)  

Add ground:

1. Hierarchy → Right click → 3D Object → Plane  
2. Rename it to: Ground  
3. Set Transform:

Scale: (3, 1, 3)  
Position: (0, 0, 0)

---

## Step 5 – Setup Teleportation

1. Select Ground  
2. Inspector → Add Component → search Teleportation Area → add it  

Ensure Ground has a collider (Mesh Collider is added by default for Plane).

---

## Step 6 – Test VR

1. Click Play  
2. If a headset is connected, you should see a teleport ray or arc  
3. Aim at the ground and teleport  

---

## Step 7 – Add Objects

Add the following objects:

- Cube  
- Sphere  
- Capsule  

Menu path:

Hierarchy → Right Click → 3D Object → select object  

Place them above the ground plane.

---

## Submission Task

Record a 30–60 second demo video showing:

- Scene running  
- Teleporting  
- Cube, Sphere, and Capsule visible  
- Optional controller movement  

Video filename format:

Lab01_<YourITNumber>.mp4

Example:

Lab01_IT21012345.mp4

---

## What to Submit

Submit BOTH of the following:

1) Unity project folder (NOT zipped)

Folder name:

Lab01_ManualVR_URP

Upload the entire folder with all files.

2) Demo video file

Lab01_<YourITNumber>.mp4

Both items are mandatory.
---

## Common Problems and Fixes

- No teleport ray → Check Teleportation Area is added to Ground  
- Controllers not working → Check OpenXR controller profile  
- Black screen → Check OpenXR is enabled in XR Plug-in Management  
- Input errors → Restart Unity after installing Input System  
- Camera height incorrect → Adjust XR Origin Y position  

---

## Next Lab

Lab 02 will start the main continuous VR project using the Unity VR Core Template.

This Lab 01 project will NOT be reused.

---
