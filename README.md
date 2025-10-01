# 🏫 Campus Route Optimisation — Anna University CEG Campus 2024

A web-based route optimization system tailored for **Anna University – CEG campus**, designed to help users navigate to nearby locations efficiently on campus.

Users can view live location, nearby places, optimized paths, and project information through an intuitive web interface.

---

## 📂 Project Structure

    ├── IT-Company-Website-main.zip
    ├── app.py
    ├── index.html
    ├── liveloc.html
    ├── nearby.html
    ├── nearby.py
    ├── project.html
    ├── project.js
    └── project_1.html



- `app.py` — Main backend (Flask or Python-based) for route logic  
- `nearby.py` — Backend module for nearby-point calculations  
- `index.html`, `project.html`, `project_1.html` — Frontend pages  
- `liveloc.html` — Page to show live user location  
- `nearby.html` — Page to show nearby places  
- `project.js` — Frontend JavaScript logic  
- `IT-Company-Website-main.zip` — Possibly template or related website bundle  

---

## ℹ️ About the Project

This project aims to help students or visitors on the **Anna University CEG campus** by:

- Locating their current position in real time  
- Displaying places of interest nearby (labs, classrooms, cafeterias, etc.)  
- Suggesting optimized routes (shortest paths) between points  
- Providing an engaging UI to navigate campus effectively  

It combines frontend web pages with Python backend logic to handle mapping, route planning, and spatial queries.

---

## 🔧 Features

- 📍 Live location tracking on campus  
- 📌 Nearby places discovery (labs, facilities, departments)  
- 🛤 Route optimization between source and destination  
- 🌐 Web interface to navigate through pages and features  
- 🧠 Integration of Python backend logic using `app.py` and `nearby.py`  

---

## 🛠 Tech Stack

- **Backend:** Python (Flask or similar)  
- **Frontend:** HTML, CSS, JavaScript  
- **Spatial / Geo logic:** (You may use libraries like geopy, networkx, or custom graph algorithms)  
- **Templates / UI Pages:** HTML & JS pages like `index.html`, `liveloc.html`, `nearby.html`, `project.html`  

---

## 🚀 How to Run Locally

1. **Clone the repository**

    ```bash
    git clone https://github.com/Ravi2ie/CAMPUS_ROUTE_OPTIMISATION-ANNA_UNIVERSITY_CEG_CAMPUS_2024-.git
    cd CAMPUS_ROUTE_OPTIMISATION-ANNA_UNIVERSITY_CEG_CAMPUS_2024-
        `

2. **Set up environment (optional)**

    ```bash
    python3 -m venv venv
    source venv/bin/activate   # Windows: venv\Scripts\activate


3. **Install dependencies**

If you have a requirements.txt, use:

    
    pip install -r requirements.txt


Otherwise, manually install needed modules (Flask, geospatial libs, etc.):

     pip install flask

# plus any others your code uses


4. **Run the application**

    ```bash
    python app.py


By default, it will run on http://127.0.0.1:5000 (unless specified differently in your code).

5. **Open in browser**

Navigate to:


    / → Home / index
    
    /liveloc → Live location page
    
    /nearby → Nearby places
    
    /project → Project information pages

## 🔮 Future Enhancements

  - Interactive campus map with drag-and-drop route planning
  
  - Use map APIs like Google Maps, OpenStreetMap or Leaflet
  
  - Add user authentication (login, roles)
  
  - Real-time updates and mobile responsiveness
  
  - Optimize routes based on time, congestion, walking distance
  
  - Visual enhancements, map overlays, and GPS integration

## 🤝 Contributing

- Contributions are welcome!

- Fork this repository

1. **Create a new branch:**

    ```bash
    git checkout -b feature-name


2. **Commit your changes:**

    ```bash
    git commit -m "Add route optimization feature"


3. **Push to your branch:**

    ```bash
    git push origin feature-name


4. **Create a Pull Request describing your changes**
