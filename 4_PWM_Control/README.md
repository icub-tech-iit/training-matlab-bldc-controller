# Simulink implementation simulating the Back-EMF Voltage of a BLDC Motor


## 🛠 Model and Setup

The provided model lets you simulate a BLDC motor which is driven by a three-phase inverter. Three-phase voltages are modulated directly using PWM that is implemented under the commutation logic subsystem.


| ![](assets/block_diagram.PNG) |
| :---------------: |


## What's new?!
1. Added a PWM generator which take the duty cycle as an input and output a pulse that switch between the 2 commutation logics.

⚠ Many configuration parameters of the model has been changed respect to the others implementations.

| ![](assets/pwm_commutation_logic.PNG) |
| :---------------: |


## Usage

You can do the following with the provided files:

- Run Simulink model (Modeling_commutation_logic.slx) and open up the Data Inspector to view the logged signals such the desired and measured speeds and supplied voltage to the three-phase inverter.
