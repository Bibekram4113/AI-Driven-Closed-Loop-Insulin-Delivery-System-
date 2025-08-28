# AI-Driven Closed-Loop Insulin Delivery System  

A prototype **closed-loop insulin pump** designed for **Type-2 Diabetes management**.  
The system uses **MATLAB-based glucose-insulin modeling** and an **embedded control loop** to automatically regulate insulin infusion, demonstrating the feasibility of **personalized and continuous therapy**.  

---

**## 🎯 Features  **
- 🧪 **Closed-loop feedback control** for real-time glucose regulation  
- 📈 **MATLAB simulation** of glucose-insulin dynamics  
- 💉 Automated insulin infusion with algorithm-driven syringe pump control  
- ⚙️ Customizable parameters for **personalized therapy**  


**⚙️ Methodology**
Glucose-Insulin Modeling

Used mathematical models of glucose-insulin interaction.

Simulated blood glucose variation under meals and insulin injections.

Closed-Loop Control

PID/algorithmic controller adjusts insulin infusion rate in real time.

Maintains glucose within safe physiological range.

Embedded Implementation

Control signals simulated for integration with syringe pump hardware.

Designed for future hardware deployment.

**▶️ Usage**
Open MATLAB and load the simulation scripts (/src/glucose_insulin_model.m).

Run the model to simulate glucose-insulin dynamics.

Adjust control parameters (PID gains) for different patient scenarios.

Observe insulin delivery and blood glucose response graphs.

**📊 Results**
Successfully demonstrated closed-loop control of glucose in simulations.

Algorithm automatically maintained glucose within safe levels despite meal disturbances.

Validated personalized insulin therapy feasibility through adaptive parameter tuning.

**🔮 Future Work**
Integrate with actual syringe pump hardware using microcontrollers.

Enhance with AI-based adaptive controllers (Reinforcement Learning, LSTMs).

Develop wearable IoT-based closed-loop system for real-time patient monitoring.

