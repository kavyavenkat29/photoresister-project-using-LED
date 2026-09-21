# # Phototransistor Light-Sensing Circuit 

# ## 📖 Description 

This setup demonstrates a **light-sensing breadboard circuit** that uses a phototransistor sensor module powered by a 9V DC battery. 

The circuit harnesses the optical response of the sensor module to trigger a **blue output LED** when light levels change or when the sensor is covered. 

A **red LED** integrated onto the module board serves as a power indicator. 

# ## 🛠 Materials Required 

- **9V Battery**: Hi-Watt 9V DC battery with clip/snap connector 

- **Solderless Breadboard**: Standard white breadboard for prototyping 

- **Phototransistor / Light Sensor Module**: Sensor board with optical sensing element 

- + onboard red power LED 

- **Blue LED**: 5mm indicator LED 

- **Jumper Wires**: Flexible Dupont jumper cables (red, black, orange, brown, grey) 

- **Resistors**: Current-limiting and pull-down resistors 

# ## ⚙️� Procedure 

1. **Power Rail Connection** 

- Connect the red positive lead and black ground lead from the 9V battery clip into the breadboard rails. 

2. **Mounting the Sensor** 

- Insert the phototransistor sensor module into the center of the breadboard. 

3. **Powering the Module** 

- Connect VCC and GND pins of the sensor module to the breadboard rails. 

- Confirm the onboard **red LED** turns on (power indicator). 

4. **Connecting the Output LED** 

- Wire the sensor’s output pin to the anode of the **blue LED**. 

5. **Completing the Ground Loop** 

- Connect the cathode of the blue LED (through a resistor) back to the ground rail. 

6. **Testing the Circuit** 

- Cover or shade the sensor element with your finger. 

- Verify that the **blue LED illuminates** when light is blocked. 

# ## ⚠️� Notes 

- Always check polarity of the battery clip, sensor pins, and LEDs before powering. 

- **Red LED** = module powered. 

- **Blue LED** = sensor output triggered. 

# ## 📖 Conclusion 

The phototransistor circuit successfully demonstrates **light-dependent switching** on a solderless breadboard. 

Powered by a 9V battery, the sensor module drives a blue LED output whenever light levels change, making it a simple and effective educational prototype. 

