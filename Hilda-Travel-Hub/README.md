HILDA TRAVEL HUB

Hilda Travel Hub is a simple and responsive travel blog website developed using HTML, CSS, and JavaScript. The website showcases beautiful travel destinations, useful travel tips, and a newsletter subscription form. It is designed with a modern, colorful interface that provides users with an enjoyable browsing experience.

Project Features

• Responsive navigation menu
• Hero section with a travel-themed background
• Featured travel destinations
• Travel tips section
• Latest travel blog posts
• Newsletter subscription form with email validation
• Modern card hover animations
• Mobile-friendly responsive design
• Attractive user interface

Technologies Used

• HTML5
• CSS3
• JavaScript
• Font Awesome
• Google Fonts (Poppins)

Project Structure

Hilda-Travel-Hub/

index.html

about.html

contact.html

destinations.html

css/
    style.css

js/
    script.js

images/
    paris.webp
    Zanzibar.jpg
    Tokyo.webp
    Beaches.webp
    Mountain.avif
    cities.jpg

Dockerfile

README.md

.github/
    workflows/
        deploy.yml

How to Run the Project

1. Download or clone the project.
2. Open the project folder in Visual Studio Code.
3. Ensure all images are inside the images folder.
4. Open index.html in your web browser or use the Live Server extension in Visual Studio Code.

Docker Instructions

To build the Docker image:

docker build -t hilda-travel-hub .

To run the Docker container:

docker run -d -p 8080:80 hilda-travel-hub

Open your browser and visit:

http://localhost:8080

Author

Hilda

Year

2026