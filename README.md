# 🌡️ **SystemTempMonitor: Monitoring Your System's Temperature**

<p align="center">
  <img src="https://github.com/AugustoPerboni/system-temp-monitor/assets/120643495/0dd701e1-ddb4-4980-963f-2e4a44885714" alt="Image">
</p>


**About SystemTempMonitor:**  
SystemTempMonitor is a handy shell script that keeps tabs on your computer's crucial temperature data. It monitors the CPU, GPU, and SSD temperatures, ensuring your system stays within safe operating ranges. Works only with NVIDIA GPU's.

### 🚀 **Features**
- **Real-time Monitoring**: Get instant updates on CPU, GPU, and SSD temperatures.
- **Automated Setup**: Easily install lm-sensors for hassle-free temperature monitoring.
- **Nvidia GPU Support**: Includes Nvidia GPU temperature monitoring.
- **User-Friendly**: Simple script with clear temperature reporting.
- **Hardware Safety**: Protect your hardware by preventing overheating.

## 📋 **Usage**

1. Ensure that the appropriate NVIDIA driver is installed.
2. Add the script to your system's path for easy access as a command.
   
   `sudo cp SystemTempMonitor.sh /usr/local/bin/temperatures`
   
   `sudo chmod +x /usr/local/bin/temperatures`
   
3. Run the script:
   `SystemTempMonitor`.
4. View CPU, GPU, and SSD temperatures in real-time using the `watch` command:
    `watch -n 1 temperatures`

## 🤝 **Contributing**

Contributions are welcome! Feel free to open issues, suggest improvements, or submit pull requests.

## 📝 **Author**

Augusto Perboni

## 🙏 **Acknowledgments**

- Special thanks to the lm-sensors and Nvidia communities for their invaluable tools and resources.
