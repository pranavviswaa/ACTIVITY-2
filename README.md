# **Cyber Range as a Service – Attack & Defense Simulation**

**Activity 2 Report**

---

## **1. Introduction**

With the rapid growth of digital infrastructure, cybersecurity has become a critical concern for organizations and individuals. Traditional learning methods are often insufficient to understand real-world cyber threats. A **Cyber Range** is a virtual environment designed to simulate cyber attacks and defense mechanisms in a controlled setting.

This project focuses on developing a **GUI-based Cyber Range Simulator** using Python. It allows users to simulate cyber attacks and observe how defensive mechanisms respond in real time. The system provides a practical platform for understanding cybersecurity concepts interactively.

---

## **2. Objectives**

The main objectives of this project are:

* To design and develop a GUI-based cyber attack-defense simulator
* To simulate common cyber attacks such as brute force and DDoS
* To implement basic defense mechanisms like intrusion detection and rate limiting
* To provide real-time monitoring and logging of system activities
* To enhance understanding of cybersecurity through practical simulation

---

## **3. Technologies Used**

| Technology              | Purpose                             |
| ----------------------- | ----------------------------------- |
| Python                  | Core programming language           |
| Tkinter                 | GUI development                     |
| Random / Time libraries | Simulation control                  |
| Scikit-learn (optional) | Basic AI-based detection            |
| GitHub                  | Version control and project hosting |

---

## **4. System Architecture**

The system is divided into the following modules:

### **4.1 GUI Module**

* Provides user interface for interaction
* Allows users to select attack types and initiate simulation

### **4.2 Attack Module**

* Simulates different types of cyber attacks
* Generates attack traffic and events

### **4.3 Defense Module**

* Detects malicious activity
* Applies defense mechanisms such as blocking or limiting access

### **4.4 Logging Module**

* Records system events
* Displays real-time logs in GUI

---

### **Architecture Flow**

```
User → GUI → Attack Module → Defense Module → Logging System → Output Display
```

---

## **5. Implementation**

### **5.1 GUI Implementation**

The graphical user interface is built using Tkinter. It includes:

* Buttons to start attack simulations
* Text area for displaying logs
* Options to select different attack types

### **5.2 Attack Simulation**

#### **Brute Force Attack**

Simulates repeated login attempts:

* Multiple password attempts are generated
* The system tracks the number of attempts

#### **DDoS Attack Simulation**

* Simulates multiple requests sent rapidly
* Represents server overload conditions

---

### **5.3 Defense Mechanism**

#### **Intrusion Detection System (IDS)**

* Detects unusual patterns such as repeated login attempts

#### **Rate Limiting**

* Limits number of requests per second

#### **Blocking Mechanism**

* Blocks suspicious activity after threshold is exceeded

---

### **5.4 Logging System**

* Displays:

  * Attack type
  * Number of attempts
  * Detection status
  * Action taken (Blocked / Allowed)

---

## **6. Working Process**

1. User launches the application
2. GUI displays available attack options
3. User selects an attack and clicks "Start"
4. Attack module begins simulation
5. Defense module monitors activity
6. If malicious behavior is detected:

   * System applies defense (block / limit)
7. Logs are displayed in real-time
8. Simulation ends after predefined conditions

---

## **7. Results**

The system successfully demonstrates:

* Simulation of cyber attacks
* Detection of malicious activities
* Real-time response from defense mechanisms
* Clear visualization through GUI logs

### **Sample Output:**

```
[INFO] Brute force attack started
[WARNING] Multiple failed login attempts detected
[ALERT] Intrusion detected – Blocking IP
[INFO] Attack stopped
```

---

## **8. Advantages**

* Easy to use graphical interface
* Helps in understanding real-world cyber threats
* Safe environment for experimentation
* Expandable with advanced features

---

## **9. Limitations**

* Simulated environment (not real network traffic)
* Basic attack scenarios
* Limited AI capability (if not implemented)

---

## **10. Future Enhancements**

* Integration of advanced AI-based threat detection
* Real-time network visualization
* Multi-user simulation environment
* More attack scenarios (SQL injection, ransomware, etc.)
* Web-based deployment

---

## **11. Conclusion**

This project demonstrates the concept of a Cyber Range by simulating attack and defense scenarios in a controlled environment. It provides a hands-on learning experience and improves understanding of cybersecurity concepts. The system can be further enhanced with advanced technologies to make it more realistic and powerful.

---

## **12. References**

* Python Documentation: https://docs.python.org
* Tkinter GUI Guide
* Cybersecurity Fundamentals (Online Resources)

---

**Submitted By:**
PRANAV VISWAA

**Course:** Cyber Security Lab

**Date:**26/04/2026

---
