# WebXR Experience - VR & AR

This project showcases a WebXR experience where users can explore immersive environments in **Virtual Reality (VR)** and interact with objects in **Augmented Reality (AR)**. Using web technologies such as [A-Frame](https://aframe.io/) and [AR.js](https://github.com/jeromeetienne/AR.js) for creating 3D environments and AR interactions, providing an engaging way to demonstrate the power of WebXR.

## Features

-   **Virtual Reality (VR)**: Experience a 360° virtual tour with a customizable environment and 3D models.
-   **Augmented Reality (AR)**: Interact with 3D objects in real-world surroundings using AR markers.
-   **Responsive UI**: Easy navigation between AR and VR experiences with user-friendly buttons.
-   **Interactive Design**: Includes navigation buttons for returning to the main menu and seamless transitions.

## Technologies Used

-   **[A-Frame](https://aframe.io/)**: A web framework for building 3D/VR experiences.
-   **[AR.js](https://github.com/jeromeetienne/AR.js)**: A library for marker-based AR experiences.
-   **HTML5** and **CSS3**: For structuring and styling the application.
-   **JavaScript**: For interactivity and navigation.

## Setup

### Prerequisites

-   A web server to host the HTML files locally or on the internet (like [http-server](https://www.npmjs.com/package/http-server) or [nginx](https://nginx.org/)).

### Running Locally

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/webxr-experience.git
    ```

2. Navigate to the project directory:

    ```bash
    cd webxr-experience
    ```

3. Serve the files using a web server:

    - With `http-server` (Node.js required):

        ```bash
        npx http-server
        ```

    - Alternatively, you can use any web server of your choice (e.g., Nginx or Apache).

4. Open the application in your browser at [http://localhost:8080](http://localhost:8080).

## Navigation

-   **Main Menu (index.html)**: Start the experience and choose between VR and AR.
-   **VR Experience (vr-experience.html)**: Enter the virtual world and explore a 360° environment.
-   **AR Experience (ar-experience.html)**: Interact with objects in augmented reality.

## File Structure

-   **index.html**: Main menu for selecting VR or AR experiences.
-   **vr-experience.html**: VR experience with a 360° view and 3D character model.
-   **ar-experience.html**: AR experience with marker-based object interaction.
-   **/images**: Contains assets like textures and images for the experiences.
-   **/models**: Contains 3D models used in the VR experience.
