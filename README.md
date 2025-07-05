# Network Performance Dashboard 🚀

A simple and beginner-friendly project that logs ping, download, and upload speed using C++ and visualizes them using a live HTML dashboard.

## 🔧 Technologies Used
- C++
- HTML, CSS, Chart.js
- CSV file storage (no database)

## 📊 Features
- Logs timestamp, ping (ms), download (Mbps), upload (Mbps)
- Saves data in `network_data.csv`
- Displays graph using Chart.js (dashboard.html)

## 🧪 How to Run

### Part 1: Logger (C++)
1. Open `network_logger.cpp` in Code::Blocks  
2. Click **Build and Run**
3. It will create/update a file `network_data.csv`

### Part 2: Dashboard (HTML)
1. Open `dashboard.html` in your browser  
2. It will read `network_data.csv` (or manually entered JSON)  
3. You’ll see beautiful live charts 📈

## 📁 Sample Output (CSV file)

| Timestamp           | Ping (ms) | Download (Mbps) | Upload (Mbps) |
|---------------------|-----------|------------------|----------------|
| 2025-06-29 22:10:01 | 42        | 75               | 30             |

## 🖼 Screenshot

![image](https://github.com/user-attachments/assets/77b20324-c76d-4bc2-9729-5cccb3529ab7)


## 📄 License
MIT License
