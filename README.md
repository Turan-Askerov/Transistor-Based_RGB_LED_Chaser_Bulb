🌈 DIY RGB LED Bulb Upgrade

🎯 Project Goal

The aim of this project is to convert a standard non-RGB LED bulb into a custom RGB bulb. The original LED module was removed and replaced with hand-assembled RGB LEDs, controlled by a custom- built transistor-based sequential driver circuit.

🛠️ Components

💡 Standard LED bulb housing (original LED module removed)

🔵 1 × Blue LED (≈ 3V)

🟢 1 × Green LED (≈ 3V)

🔴 2 × Red LEDs (≈ 2V, used twice due to lower brightness)

🔌 USB 5V power source

🔧 Transistors (for switching)

🔋 Capacitors (for timing)

🧲 Resistors (current limiting and biasing)

🪛 Hand-soldered connections on a custom layout

⚙️ Circuit Function

- The circuit uses transistors, capacitors, and resistors to sequentially switch between different LEDs.

- Each LED lights up in turn, creating a color-changing effect without any microcontroller.

- The design is similar to a 3-bit asynchronous counter or a LED chaser circuit.

🔌 Working Principle

- Power Input: The circuit is powered via a 5V USB adapter.

- Sequential Switching: The RC (resistor–capacitor) networks control transistor switching times.

- LED Order: Blue → Green → Red → Red (repeated cycle).

- Visual Effect: A smooth cycling RGB effect, turning a normal LED bulb into a custom RGB lamp.

📷 Project Image

✨ Key Points

- Fully hand-built without using microcontrollers.

Based on transistor logic and timing circuits.

Custom LED arrangement allows brightness balancing between colors.
