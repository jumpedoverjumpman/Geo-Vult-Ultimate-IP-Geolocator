# 🌍 Geo-Vult-Ultimate-IP-Geolocator

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/License-MIT-red?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-green?style=for-the-badge" alt="Maintained">
</p>

**Geo-Vult** is a high-precision IP intelligence and interactive mapping suite. Developed for deep reconnaissance, it transforms a simple IP address into a comprehensive geographical and network profile, complete with interactive visual mapping.

---

## 🔥 Key Features

* 🎯 **Deep Intelligence:** Fetches Country, State, City, ZIP, and Timezone.
* 📡 **Network Forensics:** Identifies ISP, ASN, and Organization details.
* 🚩 **Detection Flags:** Automatically detects Hosting/Data Center infrastructure.
* 🗺️ **Interactive Maps:** Generates a custom `Leaflet.js` map via Folium with a red precision radius.
* 📊 **Multiple Formats:** Provides coordinates in Decimal, DMS, and GeoHash.
* 💾 **Auto-Export:** Saves every search as a timestamped `.txt` report and a standalone `.html` map.

---

## 📸 Preview

### Terminal Interface
The tool features a clean, stylized ASCII header and color-coded status updates for a professional OSINT feel.

### Interactive Map Output
The tool generates a high-detail map including:
* A custom marker at the coordinates.
* A red accuracy circle visualizing the location radius.
* Street-level detail using OpenStreetMap data.

---

## 🛠️ Installation

### 1. Clone the repository
```bash
git clone [https://github.com/jumpedoverjumpman/Geo-Vult-Ultimate-IP-Geolocator.git](https://github.com/jumpedoverjumpman/Geo-Vult-Ultimate-IP-Geolocator.git)
cd Geo-Vult-Ultimate-IP-Geolocator
````

### 2\. Install Dependencies

```bash
pip install requests folium geopy
```

-----

## 🚀 Usage

Run the main script:

```bash
python geo-vult.py
```

  * **Targeted Search:** Enter any IPv4 address (e.g., `8.8.8.8`).
  * **Self Search:** Press **Enter** without typing an IP to locate your own network footprint.
  * **View Map:** Choose `y` when prompted to launch the interactive map in your default browser.

-----

## 🧮 Technical Details

Geo-Vult utilizes the **Nominatim** geocoding engine via `geopy` to reverse-locate coordinates and `folium` to render spatial data. The visual red radius is calculated based on the reported accuracy of the IP data point:

$$Radius_{circle} = Accuracy_{km} \times 1000$$

-----

## 🤝 Contributing

Contributions are welcome\! If you want to add features like batch IP processing, VPN detection, or API rotation:

1.  Fork the Project.
2.  Create your Feature Branch.
3.  Open a Pull Request.

-----

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

-----

**Developed with ❤️ by [jumpedoverjumpman](https://www.google.com/search?q=https://github.com/jumpedoverjumpman)**

```
```
