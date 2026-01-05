# 🌟 stm32-rtos-wifi-led-control - Control Your LED with Wi-Fi

## 🚀 Getting Started

Welcome to the stm32-rtos-wifi-led-control project! This application allows you to control LED lights using Wi-Fi. It uses the ESP8266 Wi-Fi module and is built on FreeRTOS, making it efficient and reliable. You can easily monitor and manage your LEDs over the network.

## 📦 Download & Install

To get started, you need to download the application. Please visit the link below:

[![](https://img.shields.io/badge/Download%20Now-%20brightgreen)](https://github.com/Hoangchau1111/stm32-rtos-wifi-led-control/releases)

Once on the Releases page, locate the latest version and download the files suitable for your hardware setup. 

Here is the direct link to the Releases page for your convenience: [Download Releases](https://github.com/Hoangchau1111/stm32-rtos-wifi-led-control/releases).

## 💻 System Requirements

To run this application, you will need:

- STM32F407 microcontroller
- ESP8266 NodeMCU Wi-Fi module
- USB to UART converter (if not using NodeMCU)
- Basic understanding of connecting hardware components

## 🔌 Setup Instructions

1. **Hardware Setup:**
   - Connect the STM32F407 to the ESP8266 NodeMCU using the UART interface.
   - Ensure all connections are secure to avoid hardware communication issues.

2. **Software Configuration:**
   - After you have downloaded the application, extract the files.
   - Open them in a compatible Integrated Development Environment (IDE), such as STM32CubeIDE.

3. **Build and Upload:**
   - Compile the code within the IDE.
   - Once compiled, upload the firmware to your STM32F407 microcontroller.

4. **Connect to Wi-Fi:**
   - Use the provided configurations to connect your board to your Wi-Fi network. This will allow you to control the LED wirelessly.
   
## 🌐 Web Interface

The application provides a user-friendly web interface. Here’s how to access it:

1. Connect your device and board to the same Wi-Fi network.
2. Open a web browser.
3. Enter the IP address of your STM32F407. This address is usually displayed on the serial monitor during startup.
4. Use the web interface to turn LEDs on and off.

## 🔧 Features

- **Dual-UART Architecture:** Allows for efficient communication between devices.
- **Thread-Safe Logging:** Safely log messages without interference from other processes.
- **Bidirectional PING/PONG Monitoring:** Check connectivity between your devices effortlessly.
- **Watchdog System:** Ensures the system remains operational by resetting the microcontroller if it becomes unresponsive.
- **Responsive Web Interface:** Easily control your LEDs from any device with a browser.

## 🛠️ Troubleshooting

If you encounter any issues, consider the following:

- Ensure the hardware connections are correct and secure.
- Double-check the Wi-Fi credentials in your code.
- Restart the microcontroller and your router to clear any temporary network issues.
- Refer to the logs for diagnostic messages. This can help identify where the issue may be.

## 🤝 Community and Support

If you have questions or need additional help, feel free to join the community:

- Visit the [GitHub Issues page](https://github.com/Hoangchau1111/stm32-rtos-wifi-led-control/issues) to report bugs or request features.
- Check the discussions for tips and shared experiences with other users.

## 📝 Additional Resources

For more information about the technologies used in this project, consider the following topics:

- [FreeRTOS Documentation](https://www.freertos.org/)
- [ESP8266 NodeMCU Guide](https://nodemcu.readthedocs.io/en/release/)

## 🔗 License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software as you wish.

**Ready to take control of your LEDs?** Visit the link below to download the software and start your journey!

[![](https://img.shields.io/badge/Download%20Now-%20brightgreen)](https://github.com/Hoangchau1111/stm32-rtos-wifi-led-control/releases)