🖥️ Roche Site IT Support Hub

A streamlined, interactive troubleshooting dashboard designed to fast-track solutions for workstation hardware and meeting room equipment at Roche.

## 🎯 Purpose
This hub serves as a first-line diagnostic tool for employees to resolve common technical challenges independently before raising a formal IT ticket. It covers:
* **Monitor Issues**: Power checks and LED diagnostics.
* **Docking & Charging**: HP USB-C Docking troubleshooting and hard reset procedures.
* **No Signal**: Cable seating and power cycle steps.
* **Meeting Room AV**: Polycom Studio Audio/Video alignment and Google Meet configuration.

## ✨ Key Features
* **Keyword Search**: Quick access to troubleshooting steps via the search bar.
* **Visual Guides**: High-quality reference images for cable placements and LED statuses.
* **Responsive Design**: Built with Tailwind CSS for seamless use on laptops and mobile devices.
* **Smart Navigation**: A "History Stack" implementation allows users to navigate back and forth through troubleshooting steps without losing progress.
* **Escalation Links**: Direct integration with ServiceNow for raising OnSite IT or Facilities (OFM) tickets when manual fixes fail.

## 🛠️ Tech Stack
* **HTML5 / CSS3**
* **JavaScript (Vanilla)**
* **Tailwind CSS** (via CDN)
* **Google Fonts** (Inter)

## 📂 Project Structure
* `index.html`: Main application logic and UI structure.
* `*.jpg`: Visual assets for hardware components and step-by-step guides.

## 📝 Maintenance Note
To update troubleshooting steps or images:
1.  Add new images to the root directory.
2.  Update the corresponding `div` IDs in the `index.html`.
3.  Modify the `handleSearch` function to include new keywords for the search bar.

---
*Built for Roche Site IT | © 2026*
