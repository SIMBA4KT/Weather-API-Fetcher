#  Weather API Fetcher 🌤️

A lightweight command-line Python application that connects to real-time weather endpoints to fetch, parse, and display current meteorological data and forecasts efficiently.

---

## Features

* **Real-Time Data Retrieval:** Queries live weather metrics directly from public APIs (such as Open-Meteo).
* **JSON Payload Parsing:** Efficiently extracts key meteorological indicators like temperature, wind speed, humidity, and atmospheric conditions.
* **Command-Line Interface (CLI):** Clean, fast, and lightweight execution directly from your terminal.

---

## Tech Stack Used

* **Backend:** Python 3.x
* **Core Libraries:** `requests` / standard library modules (for API calls and JSON parsing)
* **Frontend :** TypeScript, HTML/CSS
* **Architecture:** Polyglot setup handling backend logic via Python services and type-safe client communication via TypeScript.
---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/SIMBA4KT/Weather-API-Fetcher.git](https://github.com/SIMBA4KT/Weather-API-Fetcher.git)
   cd Weather-API-Fetcher
Install dependencies:

Bash
pip install requests
Run the application:

Bash
python main.py

## Usage
Once executed, the script sends an HTTP GET request to the weather endpoint, parses the returned JSON data, and outputs structured weather updates right to your terminal window.

## Contributions 
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## License
This project is open-source and available under the MIT License.
