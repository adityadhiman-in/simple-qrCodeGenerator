# simple-qrCodeGenerator

Purpose:
This documentation outlines the functionality and usage instructions for the QR code generator script. It details how to generate a QR code image from a provided URL and save it as a PNG file, along with storing the URL into a text file.

Usage:
Installation: Before utilizing the script, ensure that the required packages are installed by executing the following command:

npm install inquirer qr-image fs

Executing the Script: Run the script using the command:

node index.js

Input Prompt: Upon running the script, it will prompt the user to enter a URL. Simply input the desired URL and press Enter.
QR Code Generation: After providing the URL, the script will generate a corresponding QR code image.
Saving Output: The generated QR code image will be saved as a PNG file named qr.image.png.
URL Storage: Furthermore, the script will save the provided URL into a text file named URL.txt.

Example:
For instance, if the user inputs the URL https://www.example.com when prompted, the script will generate a QR code image representing this URL. Additionally, it will save the URL into a text file named URL.txt with the content: https://www.example.com
