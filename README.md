# Weather API Fetcher 🌤️

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-Frontend-3178C6?logo=typescript&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

A lightweight Python application that connects to real-time weather endpoints to fetch, parse, and display current meteorological data and forecasts efficiently—backed by a polyglot architecture pairing Python backend services with a type-safe TypeScript frontend.

---

## Features

* **Real-Time Data Retrieval:** Queries live weather metrics directly from public APIs (such as Open-Meteo).
* **JSON Payload Parsing:** Efficiently extracts key meteorological indicators including temperature, wind speed, humidity, and atmospheric conditions.
* **Command-Line Interface (CLI):** Clean, fast, and lightweight execution directly from your terminal.
* **Polyglot Architecture:** Separates backend data-fetching logic in Python from type-safe client communication in TypeScript.

---

## Tech Stack

| Layer | Technologies |
| :--- | :--- |
| **Backend** | Python 3.x |
| **Core Libraries** | `requests`, Python standard library (`json`, `urllib`) |
| **Frontend** | TypeScript, HTML5, CSS3 |
| **Architecture** | Polyglot setup (Python API services + type-safe TypeScript client) |

---

## Project Structure

```text
Weather-API-Fetcher/
├── main.py              # CLI entry point & weather API request logic
├── frontend/            # TypeScript, HTML, and CSS client files
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

---

## Installation & Setup

### 1. Clone the repository
```bash
git clone [https://github.com/SIMBA4KT/Weather-API-Fetcher.git](https://github.com/SIMBA4KT/Weather-API-Fetcher.git)
cd Weather-API-Fetcher
```

### 2. Install Python dependencies
```bash
pip install requests
```
*(Or, if using a `requirements.txt` file: `pip install -r requirements.txt`)*

### 3. Run the application
```bash
python main.py
```

---

## Usage

Once executed, `main.py` sends an HTTP `GET` request to the configured weather endpoint, parses the returned JSON payload, and outputs structured weather updates directly to your terminal:

```text
Fetching weather data...

Location: Nairobi, KE
Temperature: 22.4°C
Wind Speed: 14.2 km/h
Humidity: 61%
Condition: Partly Cloudy
```

---

## Roadmap

- [x] Core CLI weather fetcher in Python
- [x] JSON response parsing for key meteorological metrics
- [ ] Interactive web dashboard with Streamlit / TypeScript UI
- [ ] Multi-day forecast visualization & unit toggling (°C / °F)

---

## Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to open an issue or submit a pull request on the [Issues page](https://github.com/SIMBA4KT/Weather-API-Fetcher/issues).

---

## License

This project is open-source and available under the **MIT License**.
