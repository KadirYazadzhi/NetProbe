# 🚀 NetProbe - Advanced Network Scanning Tool

## 🌟 Overview
NetProbe is a high-performance, multi-threaded network scanner designed for penetration testers, ethical hackers, and system administrators. It enables fast and efficient port scanning to identify open services, detect vulnerabilities, and analyze network security. This tool is built using C# and WPF, providing a user-friendly graphical interface while maintaining powerful scanning capabilities.

## 🎯 Features
✅ **Multi-threaded scanning** - Supports up to 100 simultaneous threads for rapid scanning.  
✅ **Custom port selection** - Scan specific ports, port ranges, or all 65,535 ports.  
✅ **Service detection** - Identifies common services (HTTP, SSH, FTP, etc.) running on open ports.  
✅ **Version detection** - Retrieves the version of detected services where possible.  
✅ **Tor integration** - Optionally route scans through the Tor network for anonymity.  
✅ **Export results** - Save scan data in multiple formats (JSON, CSV, TXT) for later analysis.  
✅ **Detailed and brief scan modes** - Choose between a quick summary or in-depth analysis of detected ports.  
✅ **Advanced settings** - Configure timeouts, retries, and scanning depth.  
✅ **Update checker** - Ensures you always use the latest version.  
✅ **Interactive CLI & GUI** - User-friendly interface with intuitive navigation.  
✅ **Real-time logging** - View live scan progress with detailed logs.  
✅ **IP range scanning** - Scan multiple IPs in a given subnet.  
✅ **Intelligent scanning** - Adaptive scanning strategies based on network conditions.  

## 🔧 Installation
### 🔹 Prerequisites
- Windows 10/11 or Linux (via Mono or .NET Core)
- .NET SDK installed (for building from source)

### 🔹 Steps
1️⃣ Clone the repository:
```bash
 git clone https://github.com/KadirYazadzhi/NetProbe.git
```

2️⃣ Navigate to the directory:
```bash
 cd NetProbe
```

3️⃣ Compile the project (if using .NET CLI):
```bash
 dotnet build
```

4️⃣ Run the scanner:
```bash
 dotnet run
```

Alternatively, use the precompiled executable from the **Releases** section on GitHub.

## 📜 Usage
Once started, the program presents an interactive menu in CLI:
```
NETPROBE MENU
1. Scan Ports
2. Export Results
3. View Last Scan
4. Configure Threads
5. Toggle Tor
6. Advanced Settings
7. Check for Updates
8. Exit
```
Choose an option by entering the corresponding number in CLI.

### 🔍 Scanning Ports
1️⃣ Enter the target IP, hostname, or CIDR range.  
2️⃣ Specify ports to scan:
   - Single ports: `80, 443`
   - Ranges: `20-25`
   - All ports: `all`
3️⃣ Select scan mode:
   - **Quick Scan** - Fast results with basic information.
   - **Deep Scan** - More detailed analysis, including service and version detection.
4️⃣ View the results in real-time with progress updates.

### 💾 Exporting Scan Results
After scanning, results can be exported in JSON, CSV, or TXT formats using option **2**.

### 🛠 Configuring Threads
Set the number of concurrent threads for scanning via option **4** (Default: 100).

### ⚙️ Advanced Settings
- **Timeouts**: Adjust response waiting time for slow networks.
- **Retries**: Set the number of attempts per port.
- **Scan Depth**: Choose between light or aggressive scanning.
- **Protocol selection**: TCP and future UDP support.

### 🕵️‍♂️ Enabling Tor
Toggle Tor mode via option **5** for anonymous scanning.

### 🔄 Checking for Updates
Ensure you have the latest version using option **7**.

## 🏗 Future Improvements
🚀 **Integration with Nmap for extended service detection**  
🔍 **More advanced fingerprinting techniques**  
📊 **Graphical visualization of scan results**  
📡 **Support for UDP scanning**  
🌍 **Geolocation-based analysis for scanned IPs**  
🔒 **Brute-force testing for detected services**  
📡 **Real-time network traffic analysis**  

## 📜 License
This project is licensed under the **MIT License** - see the LICENSE file for details.

### ⚖️ What does this mean?
- ✅ You are free to use, modify, and distribute this software.
- ✅ You can use it for both personal and commercial projects.
- ❌ You cannot hold the author liable for any damages or misuse.
  
---

🌟 If you like this project, consider giving it a star! ⭐



