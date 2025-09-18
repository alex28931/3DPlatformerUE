# 🧱 3D Platformer – Unreal Engine

A modular 3D platformer developed in Unreal Engine using Bleprints, featuring diverse platform types, collectible power-ups, and intelligent enemies driven by Behavior Trees and Environment Query System (EQS).

## 🎮 Gameplay Overview

- **Inheritance-Based Gameplay Elements**  
  Platforms, power-ups, and enemies are all implemented using C++ inheritance, ensuring reusable logic and easy extensibility.

- **Modular Power-Up System**  
  Power-ups derive from a common base class and offer various effects (e.g. speed boosts, jump height), designed for quick integration of new abilities.

- **Three Unique Enemy Types**  
  Enemies share a base class and behavior framework, with different behaviors configured through blackboard variables and custom task logic.

- **Environment Query System (EQS)**  
  AI agents use EQS to search for player locations, patrol zones, or strategic positions in the level, reacting contextually to their surroundings.

## 🧠 AI Architecture

- **Behavior Trees** – Core decision-making structure for all enemy types  
- **Blackboard System** – Shared configuration across enemy behaviors  
- **Custom Tasks & Decorators** – Defined in and Blueprints for specific logic  
- **EQS Integration** – For environmental awareness and dynamic movement

## 🔗 Blueprint Communication

- Utilized **Event Dispatchers**, **Blueprint Interfaces**, and **direct references** to enable seamless interaction between gameplay components (e.g. triggering power-ups, updating UI, enemy/player interactions).

## 🛠️ Technologies Used

- **Unreal Engine**
- **Behavior Trees & Blackboard**
- **Environment Query System (EQS)**
- **Inheritance-Based Design**
- **Blueprint Communication (Events, Interfaces, etc.)**

## 🎯 Development Focus

- Apply object-oriented principles to platforms, power-ups, and enemies  
- Design reactive AI with scalable behavior logic using Unreal’s tools  
- Integrate Blueprint and C++ logic for a flexible gameplay architecture  
- Use EQS for intelligent, environment-aware AI behavior

## 🎞️ Gameplay Preview

![Gameplay Preview](Gifs/Gameplay.gif)
