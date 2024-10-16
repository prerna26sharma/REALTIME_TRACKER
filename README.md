
# Real-Time Tracking App

A real-time tracking application built using Node.js, Express, Leaflet.js for maps, and Socket.IO for real-time communication. This project tracks the user's live location and displays it on a map with live updates as the location changes.

## Features
- **Real-time Location Tracking**: The app uses the browser's Geolocation API to retrieve the user's location and update it on a map in real time.
- **Interactive Map**: The map is rendered using Leaflet.js, an open-source JavaScript library for mobile-friendly interactive maps.
- **WebSocket Communication**: Uses Socket.IO to enable real-time communication between the client and server, sending the location data as it changes.
  
## Technologies Used
- **Frontend**: 
  - HTML5
  - Leaflet.js (for interactive maps)
  - Socket.IO (client-side for real-time updates)
  - CSS (for styling)

- **Backend**:
  - Node.js
  - Express.js (for server setup)
  - Socket.IO (server-side for real-time communication)


## Getting Started

### Prerequisites
Make sure you have Node.js installed. You can check if it's installed by running:
```bash
node -v
```

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/prerna26sharma/REALTIME_TRACKER.git
    ```

2. **Install dependencies**:
    Navigate into the project directory and run:
    ```bash
    npm install
    ```

3. **Run the server**:
    ```bash
    node app.js
    ```
    The app will be running at `http://localhost:3000`.

### Usage
- Open your browser and visit `http://localhost:3000`.
- Allow the browser to access your location.
- Your live location will be displayed on the map, with real-time updates as you move.

![image](https://github.com/user-attachments/assets/ff165597-a37c-40ed-98e8-9699a9bf4bed)
