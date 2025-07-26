---
layout: default
title: Ysatis Tagle — Embedded Systems Developer
---

# Ysatis Tagle — Embedded Systems Developer

Hey! I’m Ysatis — an embedded systems developer who loves designing systems that bridge hardware and software.
I focus on custom PCB design, microcontroller firmware, and real-world signal processing.

When I’m not debugging circuits, I’m usually making things: screenprinting, building DIY guitar pedals, sewing, laser cutting, 3D printing, restoring retro tech, or playing music.  
I enjoy tackling projects end-to-end — from soldering hardware to writing bare-metal firmware and building PC tools that make it all work together.

---

## Featured Projects *(In Progress)*

These projects are **works in progress** — I’m actively developing, testing, and documenting them to grow my embedded systems skills and demonstrate real-world problem solving.

---

### Analog Video to UART Converter *(In Progress)*

**Overview:**  
A custom embedded system that converts analog CVBS video to a digital stream over UART using an STM32F microcontroller and a video decoder.

**Goals:**  
- Design and fabricate a custom PCB for the STM32F + video decoder IC  
- Write bare-metal firmware in C to handle I2C configuration, video data buffering, and UART streaming  
- Verify data integrity with a logic analyzer and oscilloscope  
- Optimize for real-time performance and low-level register programming
- Free up some tapes from my camcorder!

**Repo:** [View Firmware & PCB Files](https://github.com/ytag3/analog-to-uart)

---

### PC UART Video Receiver & Visualizer *(In Progress)*

**Overview:**
A companion Python tool that will receive the video stream over UART and display it in real-time on a PC.

**Goals:**
- Build a Python script with `pyserial` for cross-platform serial communication and frame rendering
- Reconstruct and display video frames from the incoming UART stream
- Log frame stats for testing and debugging

**Repo:** [View Python Receiver Tool](https://github.com/ytag3/pc-uart-visualizer)

---

## Previous School Projects

Below are a few selected projects I completed during my academic career — each helped me build a strong foundation in the engineering design process and professional skills.

---

### Whack-a-Mole Game on BeagleBone Black

![School Project Photo](/assets/images/school-project-1.jpg)

Implemented a Whack-a-Mole game on the BeagleBone Black to learn driver development and embedded graphics. Wrote a custom frame buffer driver, designed a Qt interface for the display, and built the game logic in C++ using a state machine with software debouncing. The game supported a timer and multiple difficulty levels — our next goal was to add a global leaderboard.

---

### Sorption-Based Gas Recycling & Exhaust System (Capstone)

![School Project Photo](/assets/images/school-project-2.jpg)

Capstone project to design a modular gas recycling and exhaust system using sorption. Led team research on chemical engineering methods, realistic use cases, and prototype feasibility. Built a test bench with an Arduino, calibrated analog pressure and gas composition sensors, and wrote a Python script to capture live data and export it for analysis. Gained hands-on experience managing a team, planning with Gantt charts, and documenting the engineering design process.

---

## Skills & Tools

- Languages: **C**, **C++**, **Python**
- Platforms: **STM32F**, I2C, UART, SPI, DMA, register-level programming
- Tools: **KiCad** or **Eagle**, **STM32CubeIDE**, **pyserial**, oscilloscopes, logic analyzers, Git
- Maker Skills: Soldering, custom PCBs, 3D printing, laser cutting, retro tech repair

---

## Let’s Connect!

I’m currently seeking entry-level embedded systems opportunities where I can design, build, and debug real hardware + firmware — and keep learning by doing.  
Thanks for checking out my work — feel free to reach out if you’d like to chat or follow along!

**[LinkedIn](#)** • **[GitHub](https://github.com/ytag3)** 
