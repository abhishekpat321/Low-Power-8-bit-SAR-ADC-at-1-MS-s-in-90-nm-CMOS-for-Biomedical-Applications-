# Low-Power-8-bit-SAR-ADC-at-1-MS-s-in-90-nm-CMOS-for-Biomedical-Applications-

### 🎓 Project by: **Abhishek Patnaik (23MVD0049)**

**M.Tech – VLSI Design, School of Electronics Engineering (SENSE)**
**Vellore Institute of Technology (VIT), Vellore**
**Under the guidance of:** Dr. Prachi Sharma, Associate Professor (Grade I), SENSE



## 🧠 Abstract

Implantable and wearable biomedical devices depend heavily on accurate and energy-efficient signal acquisition. The **Analog-to-Digital Converter (ADC)** is a key component in such systems, converting analog physiological signals into digital form for further processing. However, ADCs are often among the most power-hungry blocks in medical SoCs. To address this challenge, this project proposes a **low-power, single-ended 8-bit Successive Approximation Register (SAR) ADC**, operating at a sampling rate of **1 MS/s** using a **90 nm CMOS process** and a **1.2 V supply voltage**.

The design employs four key functional blocks — **Sample & Hold circuit**, **Capacitive DAC**, **Dynamic Comparator**, and **SAR Logic** — optimized for low power and high accuracy. The **bootstrapped switch** in the Sample & Hold stage minimizes distortion and maintains constant on-resistance. The **dynamic comparator** eliminates static power consumption, operating only during clock transitions. The **binary-weighted Capacitive DAC** performs charge redistribution with good linearity, while the **SAR Logic** (based on D flip-flops) implements the binary search algorithm efficiently.

The complete schematic is designed and simulated using **Cadence Virtuoso (Spectre)** tools. The 90 nm CMOS technology node enables reduced voltage operation, smaller device sizes, and improved energy efficiency. Simulation results confirm that the proposed architecture achieves **low power consumption**, **fast decision-making**, and **high sampling accuracy**, meeting the requirements of **portable and implantable biomedical systems**.

This project contributes to sustainable and energy-efficient medical electronics design, supporting the **United Nations SDG 3 (Good Health and Well-being)** and **SDG 9 (Industry, Innovation, and Infrastructure)** by enabling compact, battery-powered diagnostic systems that enhance accessibility in healthcare technology.



## ⚙️ Project Objectives

* Design an **8-bit, 1 MS/s SAR ADC** using **90 nm CMOS technology**.
* Achieve **low power consumption** suitable for implantable and wearable devices.
* Ensure **accurate and linear signal conversion** with minimal distortion.
* Verify functionality through **simulation-based validation** using Cadence tools.
* Optimize for compactness, low area, and reduced delay.


## 🧩 System Architecture

### 🔸 Sample & Hold (Bootstrap Switch)

Captures the analog input and maintains stability during conversion.
Bootstrapped design ensures constant on-resistance and minimal distortion.

### 🔸 Dynamic Comparator

Operates in **reset** and **regeneration** phases.
Consumes **zero static power**, contributing to ultra-low total energy consumption.

### 🔸 Capacitive DAC (CDAC)

Implements **binary-weighted charge redistribution**.
Provides high linearity and low power operation — ideal for biomedical signals like ECG/EEG.

### 🔸 SAR Logic

Controls the **binary search process** using D flip-flops.
Sequentially determines each bit from MSB to LSB for accurate conversion.



## 🧮 Tools & Technologies

| Category              | Tools / Technologies                                  |
| --------------------- | ----------------------------------------------------- |
| **Design Platform**   | Cadence Virtuoso                                      |
| **Simulation Engine** | Spectre                                               |
| **Technology Node**   | 90 nm CMOS                                            |
| **Supply Voltage**    | 0.9 V – 1.2 V                                         |
| **Sampling Rate**     | 1 MS/s                                                |
| **Architecture**      | Single-ended, 8-bit SAR                               |
| **Key Circuits**      | Bootstrap Switch, Dynamic Comparator, CDAC, SAR Logic |


## 📊 Results and Discussion

* **Reduced Power:** Dynamic comparator removes static current; power consumed only during regeneration.
* **High Sampling Accuracy:** Bootstrapped switch minimizes distortion for clean analog capture.
* **Compact Design:** Single-ended structure simplifies layout and reduces capacitor count.
* **Validated Performance:** Simulation confirms **low delay**, **low power**, and **accurate bit convergence** per cycle.
* **Measured Efficiency:** Achieved significant energy reduction compared to conventional SAR ADCs.


## 💡 Advantages

✅ Low Power Consumption
✅ Low Delay and Fast Decision-Making
✅ High Sampling Accuracy
✅ Compact and Scalable Design
✅ Suitable for Biomedical and IoT Systems


## 🔮 Future Scope

* **Transistor-level sizing optimization** for enhanced accuracy.
* **Layout design and post-layout simulation** for parasitic validation.
* **Fabrication and experimental testing** of the final chip.
* **Research publication** in VLSI/EDA or biomedical electronics journals.

---

## 🌍 Societal and Environmental Impact

* Enables **low-cost, portable medical diagnostic devices**.
* Supports **remote health monitoring** and rural healthcare accessibility.
* Promotes **energy-efficient electronic design**, reducing carbon footprint.


## 👨‍💻 Author

**Abhishek Patnaik (23MVD0049)**
M.Tech – VLSI Design
Vellore Institute of Technology (VIT), Vellore

