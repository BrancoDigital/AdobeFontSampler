# Adobe Font Sampler Script

A simple InDesign script that creates a document displaying all your activated Adobe Fonts, making it easy to review and access font files through InDesign's packaging feature.

## Features
- Lists all activated Adobe Fonts with sample text
- Creates a clean, organized document
- Includes font names and character samples
- Automatically generates clickable GitHub link and timestamp
- Makes fonts accessible through InDesign's packaging feature

## Requirements
- Adobe InDesign 2024 or 2025
- Adobe Creative Cloud with activated Adobe Fonts

## Disclaimer
This is an independent project that is not affiliated with, authorized, sponsored, or endorsed by Adobe Inc. All trademarks, service marks, trade names, trade dress, product names and logos are the property of their respective owners. The script is provided "as is" without any warranties or guarantees. Use at your own risk.

## Installation

### Windows
1. Navigate to: `C:\Users\[Username]\AppData\Roaming\Adobe\InDesign\[Version]\[Language]\Scripts\Scripts Panel`

### macOS
1. Navigate to: `~/Library/Preferences/Adobe InDesign/[Version]/[Language]/Scripts/Scripts Panel`
2. You can quickly access this folder in Finder:
   - Open InDesign
   - Go to Window > Utilities > Scripts
   - Right-click (or Control-click) on "User" folder
   - Choose "Reveal in Finder"

### Installing the Script
1. Download `FontSampler.jsx`
2. Copy it to your InDesign Scripts Panel folder (paths above)
3. Restart InDesign if it was open

## Usage
1. Open Adobe InDesign 2024/2025
2. Go to Window > Utilities > Scripts
3. Double-click "FontSampler.jsx" in the Scripts panel
4. The script will create a new document with all your Adobe Fonts
5. To access the font files:
   - Go to File > Package
   - Complete the packaging process
   - Navigate to the created package folder
   - Find your fonts in the "Document fonts" folder

## Note
This script is designed to work with Adobe InDesign 2024/2025. While it may work with other versions, it has been specifically tested with these versions.

## License
[MIT License](LICENSE)
