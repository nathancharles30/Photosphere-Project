# PhotoSphere Application

## Overview

The **PhotoSphere Application** is a browser-based spatial computing project developed using **HTML, JavaScript, and A-Frame**.

The application allows users to explore an immersive **360-degree PhotoSphere environment** and interact with navigation points to move between different views or locations.

The project demonstrates how 360-degree imagery can be combined with interactive elements to create an immersive web-based spatial computing experience.

---

## Technologies Used

* **HTML5** – Used to structure the application and A-Frame scene.
* **JavaScript** – Used to control interactions, navigation, and application behaviour.
* **A-Frame** – Used to create the immersive 3D and 360-degree environment.
* **Visual Studio Code** – Development environment used to create and edit the project.
* **Live Server** – Used to run and test the application locally.

---

## Features

The PhotoSphere application includes:

* 360-degree immersive environment
* PhotoSphere imagery
* Interactive navigation buttons/hotspots
* Scene-to-scene navigation
* Mouse-based viewing
* Interactive user controls
* Browser-based 3D rendering
* JavaScript-controlled interaction
* Immersive spatial environment

---

## Controls

| Input                  | Action                                   |
| ---------------------- | ---------------------------------------- |
| **Mouse**              | Look around the 360° environment         |
| **Left Click**         | Select buttons or interactive hotspots   |
| **Navigation Buttons** | Move between available PhotoSphere views |

---

## How to Run

### Option 1 – Visual Studio Code

1. Download or clone this repository.
2. Open the project folder in **Visual Studio Code**.
3. Make sure `index.html` is present.
4. Install the **Live Server** extension if it is not already installed.
5. Right-click `index.html`.
6. Select **Open with Live Server**.
7. The application will open in your default web browser.

### Option 2 – GitHub Pages

The project can also be hosted using **GitHub Pages**.

1. Open the repository on GitHub.
2. Go to **Settings**.
3. Select **Pages**.
4. Under **Build and deployment**, select:

   * Source: **Deploy from a branch**
   * Branch: **main**
   * Folder: **/ (root)**
5. Click **Save**.
6. GitHub will generate a public webpage for the application.

---

## Project Structure

```text
PhotoSphere/
│
├── index.html
├── README.md
└── images/
```

The `images` folder contains the PhotoSphere imagery used by the application.

If additional assets are required, they can be organised into folders such as:

```text
PhotoSphere/
│
├── index.html
├── README.md
├── images/
├── audio/
└── assets/
```

---

## How the Application Works

The application uses **A-Frame** to create an immersive 360-degree environment.

A PhotoSphere image is displayed around the user's viewpoint, allowing them to look around the environment as if they are standing inside the scene.

JavaScript is used to control the interactive elements of the application. Navigation buttons or hotspots allow the user to select different locations or views.

The combination of 360-degree imagery and interactive navigation creates a simple browser-based spatial computing experience.

---

## PhotoSphere Navigation

The application uses interactive elements to allow users to navigate through the available environments.

A typical interaction is:

1. Enter the PhotoSphere environment.
2. Look around using the mouse.
3. Identify an interactive navigation button or hotspot.
4. Click the navigation element.
5. The application changes to the selected PhotoSphere or view.
6. Continue exploring the environment.

---

## User Experience

The application was designed to provide an intuitive immersive experience.

The user does not need specialist VR equipment to explore the environment. The 360-degree view can be controlled using a standard mouse and web browser.

Interactive navigation elements provide a clear way for users to move between different areas.

---

## Purpose of the Project

The purpose of this project is to demonstrate how **360-degree imagery and interactive navigation can be used within a spatial computing environment**.

The project demonstrates:

* 360-degree visualisation
* Immersive environments
* Spatial navigation
* Interactive hotspots
* Event-driven JavaScript
* A-Frame development
* Browser-based spatial computing
* User interaction within a 3D environment

---

## Known Limitations

The current version has several limitations:

* The number of PhotoSphere environments is limited.
* Navigation is based on predefined interactive points.
* The experience is primarily designed for desktop browser interaction.
* Image quality depends on the resolution of the PhotoSphere imagery.
* Advanced VR headset interaction is not currently required.

---

## Future Improvements

Potential future development could include:

* Additional PhotoSphere locations
* More interactive hotspots
* Information panels for points of interest
* Spatial audio
* Improved navigation indicators
* Animated transitions between locations
* Support for VR headsets
* Hand/controller interaction
* More detailed 360-degree environments
* Interactive objects within the PhotoSphere scenes

---

## Development

The project was developed using **Visual Studio Code** and tested using **Live Server** in a modern web browser.

**A-Frame** was used to create the immersive 360-degree environment, while **JavaScript** was used to implement navigation and interactive functionality.

---

## Author

**Nathan Charles**

Spatial Computing Portfolio Project
