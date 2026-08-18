# University Malaya Student Accommodation Finder Tool

This Shiny web application helps students explore and compare available accommodation options near **University of Malaya**, making renting and leasing much easier.
The app consists of a map-based interface, data filtering, and a searchable listings table originally sourced from multiple providers ([UM Off-Campus Accommodation — Archived](https://web.archive.org/web/20241206102931/https://hep.um.edu.my/off-campus-accommodation)).

> 📢 **UPDATE (08.2026):**  
> The original webpage no longer updates `.csv` files for student downloads. This project helped inspire the UM Accommodations management to launch an entirely new UI that dynamically charts off-campus accommodations for a smoother experience. You may visit the updated official portal at [UM Accommodation (Off-Campus)](https://hep.um.edu.my/accommodation#off-campus).

---

## ✨ Features

- 📍 **Interactive Map** of all rental properties with clustering and custom markers
- 🔎 **Filters** for:
  - 🚀 Monthly rental price range
  - 🏠 Accommodation type (Room, Apartment)
  - ✅ Location (Pantai Hillpark, Komune Living, SS2, etc.)
- 📊 **Price Distribution Plot** by category and type
- 📋 **Sortable Listings Table** with contract, price, and address details
- 📎 Clickable photo links and address popups

---

## 📁 Data Sources

This app processes and integrates listings from the official UM accommodation webpage archive:

- `Wanderlust.csv`
- `EZHOME.csv`

The app performs data cleaning, standardization, and categorization (e.g., location, type, price bracket).

---

## 🛠️ Built With

| Package        | Purpose                                          |
|----------------|--------------------------------------------------|
| `shiny`        | Web application framework                        |
| `shinythemes`  | Bootstrap-based UI themes                        |
| `tidyverse`    | Data cleaning, manipulation, and visualization   |
| `leaflet`      | Interactive map rendering                        |
| `ggmap`        | Geocoding support                                |
| `DT`           | Interactive HTML tables                          |

---

## 🌐 Live Application

You can access and interact with the live deployed application here:

🔗 **[University Malaya Student Accommodation Finder](https://eugeneloo.shinyapps.io/um-offcampus-accommodation-finder/)**
