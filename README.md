# Towards Augmenting Virtual Environments with Sound

This repository contains the **VR forest environment** developed for *Towards Augmenting Virtual Environments with Sound: A Study of Presence and User Experience*.

The environment was developed in **Unreal Engine 5** for **Meta Quest 3** and is used to investigate how different audio conditions affect presence, user experience, and stress recovery in a virtual forest setting.

## Audio Conditions

The study compares three conditions. To ensure complete experimental isolation across conditions while maintaining identical visual geometry and rendering performance, the Unreal Engine 5 scene was duplicated into three distinct level configurations:

* **Visual-Only (Silent):** Features the high-fidelity forest terrain, foliage, and dynamic lighting with all ambient and spatial audio tracks disabled.
* **Nature (Diegetic):** Integrates an ambient background nature audio track coupled with three 3D spatialized sound actors (birds calls) strategically positioned for acoustic spatialization and directional presence.
* **Nature Plus Music (Diegetic/Non-Diegetic Hybrid):** Retains the full diegetic audio setup (ambient nature background and spatialized bird actors) while layering a non-diegetic background music track (lofi piano) to evaluate the impact of musical additions on stress recovery.

## Technology

* Unreal Engine 5
* Meta Quest 3
* Meta XR Plugin
* Blueprints
* Unreal Engine audio system

> **Note:** This repository contains the forest environment and does not include the separate stress-test environment.
