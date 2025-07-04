# Thyristor-Firing-Angle-Control-for-Battery-Charger

This project demonstrates a method for controlling the charging of a battery using a thyristor (SCR) with phase angle control. By adjusting the firing angle of the thyristor, we can regulate the DC output voltage delivered to the battery, ensuring safe and efficient charging.

## 📌 Objective

To design and implement a circuit/system that:
- Uses a thyristor for AC-to-DC conversion via phase control.
- Allows adjustment of the firing angle to regulate the output voltage.
- Provides a controlled and safe charging mechanism for batteries.

## ⚙️ How It Works

A thyristor (Silicon Controlled Rectifier - SCR) acts as a switch in the AC circuit. By varying the point (firing angle) at which the thyristor is triggered within each AC cycle:
- The conduction period changes.
- The average output voltage is controlled.
- Thus, the voltage supplied to the battery is modulated.

This control method is commonly used for lead-acid batteries to prevent overcharging and extend battery life.

## 🛠️ Tools & Technologies

- 🔌 **Thyristor/SCR-based Circuit**
- ⚡ **Zero Crossing Detector** for synchronization
- 🧠 **Microcontroller / Firing Control Logic** (e.g., Arduino, 555 Timer, or DSP)
- 📐 **Simulation**: MATLAB/Simulink, Proteus, or LTspice (optional)
- 📊 **Oscilloscope / Multimeter**: To analyze waveform and output voltage

## 🧪 Features

- Adjustable firing angle control (0°–180°)
- Safe charging mechanism via voltage regulation
- Smooth DC output for battery charging
- Optionally includes closed-loop feedback using voltage sensing


## 📸 Screenshots / Waveforms

> ![image](https://github.com/user-attachments/assets/bdf02e46-0968-4bfc-b0da-2a1bdf8437be)


## 🚀 Applications

- Battery chargers (especially lead-acid)
- Industrial DC motor controllers
- Controlled rectifiers in renewable energy systems

## 🧑‍💻 Authors & Contribution

- **Soham Joshi** – Circuit Design, Code, Documentation

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).


