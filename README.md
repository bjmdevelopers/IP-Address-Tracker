# IP Address Tracker 🌍

A simple web application to track and display geolocation information for any public IP address.

## Features ✨

- 🔍 Look up any public IP address
- 🌎 Display country, region, city, and postal code
- 📡 Show ISP information
- ⚡ Auto-detect your own IP with one click
- 📱 Fully responsive design
- 🛡️ Built-in IP address format validation
- ℹ️ Clear disclaimer about postal code accuracy

## How It Works 🛠️

The application uses the [ipapi.co](https://ipapi.co/) API to fetch geolocation data for IP addresses. All processing happens client-side in the browser.

## Usage 🚀

1. Enter an IP address in the input field (e.g., `8.8.8.8`)
2. Click "Search" or press Enter
3. View the geolocation information
4. Click "Use My IP" to automatically detect and display your current IP information

## Technical Details 💻

- **Frontend**: Pure HTML, CSS, and JavaScript (no frameworks)
- **API**: Free tier of ipapi.co (1,000 requests/month)
- **Responsive**: Works on mobile and desktop devices
- **Lightweight**: Single HTML file with embedded CSS/JS

## Limitations ⚠️

- Postal codes are approximate and may not reflect exact physical location
- Mobile IPs often show carrier location rather than user location
- VPN/proxy connections will show the exit node location
- Free API tier has limited requests

## Installation 📥

No installation required! Just open the `index.html` file in any modern web browser.

For live deployment:
1. Upload the HTML file to any web hosting service
2. That's it! No server-side code required

## License 📄

This project is open source and available under the **MIT License**

## Live Demo 

[Live Demo](https://your-username.github.io/ip-tracker/)