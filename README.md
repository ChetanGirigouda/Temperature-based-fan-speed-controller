# Temperature-Based Fan Speed Control System

A smart system that automatically controls the speed of a 12V fan based on real-time temperature readings using an Arduino Uno and an LM35 temperature sensor. This project helps regulate temperature efficiently and provides a visual display of current readings via an LCD display.

## Features

- Automatic fan speed control based on temperature.
- Real-time temperature display on a 16x2 LCD.
- LED indicator for fan activation.
- Energy-efficient and responsive system.

## Components Required

| Component             | Quantity |
|-----------------------|----------|
| Arduino Uno           | 1        |
| LM35 Temp Sensor      | 1        |
| 16x2 LCD Display      | 1        |
| 12V Fan               | 1        |
| 2N2222 Transistor     | 1        |
| 1N4007 Diode          | 1        |
| 1K Resistor           | 2        |
| LED                   | 1        |
| Power Supply (5V&12V) | 1        |

## How It Works

1. The LM35 sensor measures the ambient temperature.
2. Arduino reads the sensor output and adjusts fan speed.
3. If the temperature exceeds a threshold, the fan is activated.
4. The temperature is displayed on the 16x2 LCD.
5. An LED indicates the fan's operation status.

## Getting Started

### Prerequisites

Ensure you have the following software installed:
- [Arduino IDE](https://www.arduino.cc/en/software)

### Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/temperature-fan-control.git
   (https://github.com/ChetanGirigouda/Temperature-based-fan-speed-controller)
   cd temperature-fan-control
   ```

2. Open the project in the Arduino IDE.

3. Upload the code to your Arduino Uno.

## 📋 Usage

- Power the system using the 12V and 5V supplies.
- Monitor temperature on the LCD.
- Observe automatic fan speed regulation.

## Project Demo

Add images or videos here showcasing your working project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.


