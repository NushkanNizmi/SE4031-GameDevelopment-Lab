# Lab 01 – Manual VR Setup using URP (Without VR Template)

Module: Interactive Media / VR Development  
Lab Duration: 2 Hours  
Unity Version: 6.3 LTS (or module standard LTS)  

---

## Objective

To manually configure a Virtual Reality environment in Unity using a standard 3D URP project, OpenXR, and XR Interaction Toolkit without using the VR Core Template.

This lab builds foundational understanding of VR components before working with automated templates.

---

## Learning Outcomes

After completing this lab, students will be able to:

- Create a URP project in Unity
- Install XR-related packages using Package Manager
- Enable and configure OpenXR
- Add and configure XR Origin (Action-based) manually
- Configure teleport locomotion using a floor surface
- Verify VR scene configuration using Play Mode

---

## Software Requirements

- Unity Hub
- Unity 6.3 LTS (or course-specified LTS version)
- Windows PC
- VR Headset (optional)

---

## Task Instructions

1. Create a new Unity project using the **3D (URP)** template named:

# Lab01_ManualVR_URP


2. Install the following packages from Package Manager:

- XR Plug-in Management
- OpenXR Plugin
- XR Interaction Toolkit
- Input System

3. Enable OpenXR:


# Edit → Project Settings → XR Plug-in Management → Enable OpenXR


4. Add XR Origin:


# Hierarchy → XR → XR Origin (Action-based)


5. Create a Plane named `Ground` and add:


# Teleportation Area component


6. Add the following objects to the scene:

- Cube
- Sphere
- Capsule

7. Enter Play Mode to verify setup.

---

## Submission Instructions

1. Record a **30–60 second screen video** showing:

- XR Origin in the hierarchy
- Ground object with Teleportation Area
- Play Mode running

2. Name the video file:


# Lab01_<ITNumber>.mp4


3. Upload (commit & push) the video file to this repository.

---

## Notes

- This project is only for Lab 01.
- A new project using the VR Core Template will be created in Lab 02.
- Ensure Unity version consistency across all labs.

---

## Deadline

Refer to the course LMS for the submission deadline.

---

