# QR Code Display Page
![image](https://github.com/user-attachments/assets/bfdb0c9c-d2e5-4208-a365-d9db08dfbf38)

This is a simple web page that displays a QR code which redirects users to a specific link after interaction.

## Features

- **QR Code Display**: Shows a large, centered QR code image
- **Interactive Animation**: The QR code animates when clicked
- **Click Counter**: Requires 5 clicks before redirecting
- **Progressive Web App (PWA)**: Can be installed as a standalone app
- **Social Media Integration**: Includes Open Graph and Twitter Card meta tags
- **Responsive Design**: Works on all screen sizes
- **Random Animations**: Different entrance animations each time the page loads

## How It Works

1. The page displays a QR code image (`QRImage1.png`)
2. When clicked, the QR code animates with a bounce effect
3. A click counter appears on either side of the screen
4. After 5 clicks, the user is redirected to `https://links.lukeharper.co.uk`
5. The page includes PWA capabilities for offline use and installation

## Technical Details

- **HTML Structure**: Simple page with QR code and counters
- **CSS Animations**: Multiple keyframe animations for visual effects
- **Service Worker**: Enables offline functionality
- **Web Manifest**: Defines PWA properties
- **Social Media Meta Tags**: Optimized for sharing on platforms like Twitter and Facebook

## Installation

1. Clone the repository
2. Place your QR code image in the root directory
3. Update the `manifest.json` and meta tags with your information
4. Deploy to your web server

## Dependencies

- None - this is a pure HTML/CSS/JavaScript implementation

## License

This project is open source and available under the MIT License.
