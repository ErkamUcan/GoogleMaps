# 🗺️ Google Maps Location Marker App

**Google Maps Location Marker App** is a simple Android application that demonstrates how to integrate Google Maps and display a marker on a specific location.  
Upon launching, the app centers the map on a predefined coordinate and places a marker.

---

## 🚀 Features

- 🗺 Displays Google Map on activity start  
- 📍 Places a marker on a specific LatLng location  
- 🎯 Automatically moves and zooms the camera to that location  
- 🧩 Uses SupportMapFragment and OnMapReadyCallback interface  

---

## 🛠 Technologies Used

- **Language:** Java  
- **Platform:** Android  
- **Build Tool:** Gradle (Kotlin DSL)  
- **Libraries:**
  - Google Maps SDK for Android
  - AndroidX AppCompat
  - Material Components

---

## 📱 How to Run

1. Clone the project:
   ```bash
   git clone https://github.com/your-username/GoogleMaps.git
   ```

2. Open the project in **Android Studio (Electric Eel or newer)**

3. Get a **Google Maps API Key** by following [this guide](https://developers.google.com/maps/documentation/android-sdk/get-api-key)

4. Add the API Key in `AndroidManifest.xml`:
   ```xml
   <meta-data
       android:name="com.google.android.geo.API_KEY"
       android:value="YOUR_API_KEY_HERE" />
   ```

5. Run the app on a device or emulator with internet access

---

## 📍 Default Location

- Marker Location: **LatLng(39.925533, 32.866287)**  
- Title: `"Copenhagen"`  
- Zoom Level: `12f`

> *(You can change this location by modifying `MainActivity.java`)*

---

## 📂 Project Structure

```
app/
├── src/
│   ├── main/
│   │   ├── java/com/example/googlemaps/
│   │   │   ├── MainActivity.java         # Google Maps logic & marker
│   │   │   └── MapsActivity.java         # (Empty/unused class)
│   │   └── res/layout/activity_main.xml # UI layout with MapFragment
├── build.gradle.kts                     # App-level Gradle config
build.gradle.kts                         # Project-level Gradle config
```

---

## ✅ Status

- ✅ Google Map loads on app start  
- ✅ Marker is displayed  
- ✅ Camera auto-zooms  
- ⏳ Marker click or custom UI (not implemented)

---

---

🛠️ **Note:**  
This project serves as a customizable **location marker template** using Google Maps.  
It can be easily adapted for various location-based applications such as event pins, store locators, or delivery tracking systems.  
The current implementation uses a **default marker setup** and acts as a clean starting point for further development.

[ErkamUcan]

