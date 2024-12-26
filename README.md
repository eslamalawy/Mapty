# Mapty

"Mapty" is an innovative web application that allows users to track their workouts by logging activities on an interactive map. Whether you're running, cycling, or engaging in other physical activities, Mapty helps you visualize and manage your fitness journey.

## Features

- **Interactive Map Integration:** Leverages the Leaflet library to display an interactive map for logging workout locations.
- **Geolocation Support:** Automatically detects your location for quick and easy workout logging.
- **Custom Workout Types:** Supports running and cycling activities, each with specific details like distance, duration, and additional metrics (pace for running and speed for cycling).
- **Persistent Data Storage:** Uses local storage to save workout data, ensuring workouts are not lost on page reload.
- **Responsive Design:** Optimized for all device sizes to deliver a seamless experience.

## Technologies Used

- **HTML5:** Structures the application content.
- **CSS3:** Styles the application for a clean and modern appearance.
- **JavaScript (ES6+):** Implements the app logic, including geolocation, map handling, and local storage.
- **Leaflet:** Handles the interactive map and geolocation features.


## How to Use

1. **Location Permission:** When you open the application, you will be prompted to allow the app to access your location. This is necessary to automatically detect your location for logging workouts. Click "Allow" to proceed.
   
2. **Logging a Workout:** Once the location permission is granted, click anywhere on the map to drop a marker. You will then be prompted to enter the workout details, including:
   - **Workout Type:** Choose between running or cycling.
   - **Distance:** Enter the distance covered in your workout.
   - **Duration:** Enter the duration of the activity.
   - **Additional Metrics:** Depending on the workout type, enter the pace (for running) or speed (for cycling).
   
3. **Saving the Workout:** After entering the details, click "Enter" to save your workout. The map will update with the new task marker representing your workout.

4. **Persistence of Data:** All your workout data will be saved in **local storage**, so you can revisit the application later, and your workouts will still be available even after refreshing the page.


## Live Demo

Experience the application firsthand: [![Netlify](https://img.shields.io/badge/Netlify-Deployed-blue?logo=netlify)](https://mapty-eslam.netlify.app/)

## Getting Started

To run the project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/eslamalawy/Mapty.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd Mapty
   ```

3. **Open `index.html` in your preferred web browser.**

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests to enhance the application's features and design.
