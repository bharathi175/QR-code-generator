QR Code Generator
QR Code Generator is a simple, fast, and interactive Node.js CLI tool that turns any URL into a QR code instantly. It also saves the URLs in a text file for easy reference.
Key Features
Interactive URL Input: Get URLs from users via Inquirer.js.
QR Code Generation: Creates QR code images using qr-image.
Data Persistence: Saves entered URLs in URL.txt.
Quick Output: QR images saved as qr_img.png.
Quick Start (For Developers)
To get the project running locally:

Clone the repository:
git clone https://github.com/yourusername/qr_code_project.git
cd qr_code_project

Install dependencies:
npm install

Run the project:
node index.js

Usage:
Run the project with node index.js.
Enter your URL when prompted.
A QR code image (qr_img.png) will be generated and your URL will be saved in URL.txt.

Files in this project:
index.js – Main code for generating QR codes and saving URLs.
package.json – Lists project dependencies (inquirer, qr-image).
URL.txt – Stores all URLs entered by the user.

qr_img.png – The generated QR code image.

README.md – Project documentation.
