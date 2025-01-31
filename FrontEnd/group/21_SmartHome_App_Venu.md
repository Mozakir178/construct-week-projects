### **Project: SmartHome_Manager**

**Category**: Home Automation Management

---

#### **Context**:

This project will simulate a **smart home management system** where users can control and monitor virtual devices from one place. While no real-world integration will be involved, students will **simulate device creation, management, and control** workflows to mimic the behavior of a smart home.

---

## **Project Goal**

Create a home management platform where users can add devices, configure their simulated features, set routines, monitor energy usage, and interact with appliances through a virtual dashboard.

---

## **Part 1: L1 - Minimum Expected Features**

1. **User Authentication and Household Setup**

   - Allow users to **register, log in**, and **set up a household**.
   - Users create **multiple rooms** (e.g., Living Room, Bedroom) and assign devices to each room.
   - **Example**: After logging in, the user creates a “Bedroom” and assigns devices like a virtual thermostat and lamp to it.

2. **Appliance Control Dashboard**

   - Provide a **dashboard that lists all devices** and their current states (On/Off, Temperature, etc.).
   - **Example**: On the dashboard, the user sees that the fan is off and the thermostat is set to 24°C, with options to change settings.

3. **Routine Scheduling System**

   - Simulate **routines** like turning off lights at midnight or lowering the thermostat at 8 AM.
   - **Example**: The user creates a routine that turns off all lights and fans in the house at 10 PM.

4. **Simulated Energy Usage Tracking**

   - Track how long appliances were "used" and show a **report on simulated energy consumption**.
   - **Example**: The user checks the dashboard and finds that the air conditioner has consumed 30 kWh of simulated energy over the past week.

5. **Alerts for Device Malfunctions**
   - Simulate **malfunction alerts** for devices with abnormal usage patterns.
   - **Example**: If the heater remains on for more than 24 hours, the app sends a warning recommending the device be reset.

---

## **Part 2: L2 - Unique Features**

1.  Stimulating Device Management System\*\*

        A. **Simulated Device Creation**
        - Users can **create devices** under their account, each with its own simulated features.
        - **Example**: The user creates a new device called “Smart Lamp” with configurable features like brightness control (0-100%) and color mode (Warm/Cold), with `On/Off` button and Connect `Button`
        - Another Device like `Ceiling Fan` whose features like `3 speed control`,

        B. **Configurable Features Per Device**
        - Each device will have **unique attributes** such as operational modes, thresholds, or settings.
        - **Example**:
            - A **Thermostat** allows users to set temperature limits (18°C to 30°C).
            - A **Fan** includes speed settings (Low, Medium, High).
            - A **Lamp** offers dimmer control and color selection.

        C. **Simulated Device Connection**
        - After creating a device, users must **click a "Connect" button** to simulate linking the device with the app’s management system.
        - **Example**: Once the user creates a “Smart AC,” they click "Connect," and the system shows the AC on the dashboard, ready to be controlled.

        D. **Device Status and Feedback Simulation**
        - Users can **monitor device statuses** such as whether they are "On," "In Standby," or "Malfunctioning."
        - **Example**: If the virtual washing machine fails to respond, the system simulates a malfunction warning.

---

## **Challenging Features**

1. **Simulated Usage Prediction**

   - Implement a **prediction algorithm** that learns usage patterns based on simulated logs.
   - **Example**: If the thermostat is adjusted every morning at 7 AM, the system suggests automating it for the same time daily.

2. **Emergency Mode Simulation**

   - Implement an **emergency mode** that triggers simulated actions like turning off all appliances.
   - **Example**: During emergency mode activation, the app displays that all appliances have been switched off and virtual doors are locked.

3. **Simulated Voice Control Interface**

   - Create a **text-based voice command interface** to simulate voice commands.
   - **Example**: The user types “Turn off all lights,” and the system responds by toggling all light devices off.

4. **Simulated Device Role Management**

   - Add a **multi-user role system** (Admin, Guest, Child). Different roles will have **varying access to devices and settings**.
   - **Example**: Guests can turn devices on/off, but only admins can change routines or delete devices.

5. **Simulated Device Groups for Custom Control**

   - Allow users to **group devices** to perform collective actions.
   - **Example**: A “Morning Routine” group turns on the coffee maker, lights, and TV simultaneously when activated.

6. **Simulated Energy Efficiency Recommendations**
   - Provide **simulated energy-saving suggestions** based on appliance usage patterns.
   - **Example**: The system recommends switching to a "sleep mode" routine at night to reduce the usage of unnecessary appliances.

---
