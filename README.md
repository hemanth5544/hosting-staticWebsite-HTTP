Static Website Hosting using HTTP

This repository contains a simple implementation of hosting a static website using HTTP (Hypertext Transfer Protocol). It provides a straightforward way to serve static HTML, CSS, JavaScript, and other assets to users using a basic HTTP server.


![image](https://github.com/hemanth5544/hosting-staticWebsite-HTTP/assets/92920794/379f60b4-57fe-4996-964f-b462a41ba9b5)

Table of Contents
Introduction
Prerequisites
Getting Started
Usage
Configuration
Contributing
License
Introduction
Static websites consist of fixed files that do not change, providing a cost-effective and straightforward way to host simple websites without the need for server-side processing. This repository offers a minimalistic HTTP server to serve static content to users.

Prerequisites
Before using this repository, ensure you have the following prerequisites:

Node.js installed on your machine.
Getting Started
To get started with this repository, follow these steps:

Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/hemanth5544/hosting-staticWebsite-HTTP.git
cd hosting-staticWebsite-HTTP
Install the required dependencies:

bash
Copy code
npm install
Place your static website files (HTML, CSS, JavaScript, images, etc.) inside the public directory.

Start the HTTP server:

bash
Copy code
npm start
The server will start running on port 3000 by default. You can change the port in the configuration (see Configuration).

Visit http://localhost:3000 in your web browser to view your hosted static website.

Usage
This repository can be used for simple personal websites, project demos, or any other static website that doesn't require server-side processing.

The public directory is where you should place all your static website files. You can organize your files as you see fit, but make sure the main index.html or landing page is present in this directory.

Configuration
The default configuration for the HTTP server can be found in the server.js file. If you want to modify any server settings, you can do so in this file.

For example, to change the port the server runs on, you can modify the PORT variable:

javascript
Copy code
const PORT = 3000; // Change this to your desired port number
Contributing
Contributions to this repository are welcome. If you find any issues or want to improve the implementation, feel free to create a pull request.

License
This repository is licensed under the MIT License. See the LICENSE file for more information.

Thank you for using this repository. If you have any questions or need further assistance, please feel free to reach out or open an issue in the repository. Happy hosting!




![image](https://github.com/hemanth5544/hosting-staticWebsite-HTTP/assets/92920794/379f60b4-57fe-4996-964f-b462a41ba9b5)
