# Fire Alarm Using Thermistor and NE555

This project implements a **temperature-sensitive alarm system** using a **thermistor (NTC)** and **NE555 timer IC** to provide audible warnings when the ambient temperature exceeds a predefined threshold. The system is designed for reliability, simplicity, and cost-effectiveness, making it suitable for educational purposes and practical safety applications.

---

## **Overview**
The fire alarm circuit continuously monitors temperature using a **Negative Temperature Coefficient (NTC) thermistor**. When the temperature rises beyond a certain point, the thermistor's resistance drops, triggering a 555 timer configured as an **astable multivibrator** to produce an audible alarm via a speaker.

---

## **Features**
- Temperature-based detection using NTC thermistor
- Simple, low-cost design with easily available components
- Adjustable temperature threshold by tuning resistor values
- Audible alert using a speaker driven by a power transistor
- Reliable and energy-efficient circuit

---

## **How It Works**
1. **Sensing Section**:
   - The NTC thermistor forms a voltage divider that converts temperature changes into voltage variations.
   - These changes are amplified using a transistor pair for signal conditioning.

2. **Timer Section**:
   - An **NE555 timer IC** configured in astable mode generates a pulse signal when triggered.
   - The oscillating output drives a power transistor connected to a speaker, producing the alarm tone.

3. **Triggering Mechanism**:
   - When the temperature exceeds the set threshold, the voltage across the thermistor changes, activating the transistor stage and triggering the 555 timer.

---

## **Circuit Components**
- **IC**: NE555 Timer
- **Transistors**: BC548 (NPN), BC558 (PNP), SL100B (Power NPN)
- **Diode**: 1N4001
- **Resistors**: 33kΩ, 470Ω, 560Ω, 47kΩ, 2.2kΩ, 470Ω
- **Capacitors**: 10µF, 0.04µF, 0.01µF
- **Sensor**: NTC Thermistor
- **Output**: 8Ω, 1W Speaker
- **Power Supply**: 6V DC

---

## **Applications**
- Residential fire and heat detection systems
- Industrial machinery temperature monitoring
- Data center/server room overheat alarms
- Agricultural and greenhouse temperature control
- Educational electronics projects

---

## **Circuit Diagram**
(Include an image of your circuit diagram here)

---

## **Simulation / Experimentation**
- Tested on **breadboard** and implemented on **PCB**
- Alarm successfully triggers when temperature threshold is exceeded

---

## **Future Enhancements**
- Add **adjustable temperature threshold** using a potentiometer
- Include **visual indicators** (LEDs)
- Integrate with **IoT** for remote monitoring
- Add **fail-safe mechanisms** for critical environments

---

## **References**
- [Fire Alarm Circuit Using NE555](https://bestengineeringprojects.com/fire-alarm-using-thermistor-and-ne555/)

---

### **Author**
- Shreeya Kosireddy  
- Department of Electronics & Communication Engineering  

---

### **How to Run**
1. Connect the circuit as per the provided schematic.
2. Power it with a **6V DC supply**.
3. Adjust the threshold using the resistor network.
4. The alarm will sound when the temperature exceeds the set level.

---

**Keywords:** Fire Alarm, Thermistor, NE555 Timer, Temperature Sensor, Electronics Project
