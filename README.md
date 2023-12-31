# Project Photon - The Google photos clone

A microservices-based photo gallery application designed for image upload with usage and storage monitoring. Developed using the MERN stack (MongoDB, Express.js, React.js, Node.js), the application is structured as separate microservices to enhance scalability and maintainability.

## Features

- **User Account Management:** Users can simply register and start using our application.
- **Image Upload:** Users can easily upload images using the application.
- **Image Delete:** Users can delete individual images.
- **Bulk Delete:** Users can delete their images in bulk.
- **Logging:** Tracks the activity of users.
- **Usage Monitoring:** The application provides metrics for monitoring usage patterns.
- **Storage Monitoring:** Tracks and displays storage usage for the uploaded images.

## Architecture

The microservices architecture promotes a modular and scalable design:

- **Client (React.js):** Provides the user interface.
- **Other Microservices (Node.js):** Includes services for user authentication, user activity monitoring, and storage monitoring.

## Architectural Diagram

![image](https://github.com/tayyibgondal/Project_Photon/assets/99114574/b2e359e3-b762-4604-9338-88d6054b107c)


## Application

### Landing page

![](images/1_landing_page.png)

### Gallery

![](images/2_gallery_a.png)

![](images/2_gallery_b.jpg)

### User photos page

![](images/3_my_photos_page.png)

### User activity page

![](images/4_logs.png)

### Upload images page

![](images/5_image_upload_page.png)
