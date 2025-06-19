# University Malaya Student Accommodation Finder

An interactive Shiny web application that helps students explore and compare available accommodation options near **University of Malaya**. 
The app provides a map-based interface, data filtering, and a searchable listings table sourced from multiple providers.

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

This app processes and integrates listings from UM official accomodation webpage:

- `Wanderlust.csv`
- `EZHOME.csv`

The app performs data cleaning, standardization, and categorization (e.g., location, type, price bracket).

---

## 🛠️ Built With

| Package        | Purpose                                         |
|----------------|--------------------------------------------------|
| `shiny`        | Web application framework                        |
| `shinythemes`  | Bootstrap-based UI themes                        |
| `tidyverse`    | Data cleaning, manipulation, and visualization   |
| `leaflet`      | Interactive map rendering                        |
| `ggmap`        | (Optional) Geocoding support                     |
| `DT`           | Interactive HTML tables                          |

---

