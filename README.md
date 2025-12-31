![Status](https://img.shields.io/badge/status-active-brightgreen)
[![Demo](https://img.shields.io/badge/demo-live-blue)](https://HugoMSC.github.io/OpenSpecimen/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Release](https://img.shields.io/github/v/release/HugoMSC/OpenSpecimen)](https://github.com/HugoMSC/OpenSpecimen/releases)
[![GitHub stars](https://img.shields.io/github/stars/HugoMSC/OpenSpecimen)](https://github.com/HugoMSC/OpenSpecimen/stargazers)
![HTML](https://img.shields.io/badge/html-vanilla-orange)
![CSS](https://img.shields.io/badge/css-modern-blue)
![JavaScript](https://img.shields.io/badge/javascript-vanilla-yellow)

# OpenSpecimen

**OpenSpecimen** is an open-source, self-contained website template for creating interactive type specimens on the web. It’s designed for designers, type foundries, and developers who want a clear, modern way to showcase fonts (especially variable fonts) without a heavy framework and dependencies.

---

## Table of Contents

- [About](#about)
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

---

## About

OpenSpecimen allows users to interactively explore fonts, including variable fonts. Key functionalities include:

- A glyph grid with zoomable individual glyphs, you can click in a glyph to zoom and change glyphs via the keyboard arrows 
- A live type tester with customizable axes which are automatically pulled from font metadata(weight, width, etc.)  
- Meta information display (designer, version, license) which is automatically pulled from font metadata  
- Framework-free, lightweight, and easy to deploy  

It is ideal for type designers who are not very code savvy, and anyone showcasing fonts online.

Disclaimer: I'm not a programmer. This project was developed with significant coding support and architectural guidance from Gemini 3 Flash.

---

## Demo

Check out the live demo here: [OpenSpecimen Demo](https:/HugoMSC.github.io/OpenSpecimen/)

<img width="6300" height="13929" alt="OpenSpecimen" src="https://github.com/user-attachments/assets/4f4d1061-9f4a-4818-a42e-c030b3f6c1cd" />

Current typeface being displayed by default is [Roboto](https://fonts.google.com/specimen/Roboto) by Christian Robertson.

---

## Features

- Interactive type tester for any font  
- Variable font axis sliders (weight, width, etc.)  
- Glyph grid with active highlighting and Unicode display  
- Meta information display (designer, version, license)  
- Lightweight, no external frameworks  
- Fully responsive and mobile-friendly  

---

## Installation

1. Clone the repository:
```bash
git clone https://github.com/h-msc/OpenSpecimen.git
```
2. Navigate into the project folder
3. Open index.html in a modern web browser.
No additional dependencies are required; everything runs in-browser using [opentype.js](https://opentype.js.org)

## Usage
1. Type Tester - Type any text in the interactive textarea to see it rendered in your chosen font.
   
3. Axis Sliders - Adjust variable font axes (weight, width, etc.) using the sidebar sliders. The live preview updates in real time.

3. Glyph Grid - Click any glyph to zoom in and see its Unicode codepoint. Use arrow keys to navigate between glyphs.

5. Reset Axes - Click the Reset button to return all axes and font size to default values.
   
5. Custom Fonts
   
   5.1. Replace **Roboto-VariableFont_wdth,wght.ttf** in the **fonts/** folder with your font to showcase it.
   
   5.2. Open folder in VSCode on another code editor of choice and change:
   ``` bash
   const FONT_FILENAME = 'Roboto-VariableFont_wdth,wght.ttf';
   ```
   5.3. Preview using livepreview on VSCode or another extension for your IDE of choice that allows local live preview

## Contributing
Contributions are welcome! You can help by:
- Reporting bugs or issues
- Suggesting features
- Submitting pull requests

Please follow the standard [GitHub pull request workflow](https://docs.github.com/en/pull-requests).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [opentype.js](https://opentype.js.org)
- Font designers whose works are used in demos
- Open-source community for inspiration and guidance, with focus on the incredible team at [Google Fonts](https://github.com/google/fonts), which I've become a huge fan of.

---
Thank you for exploring OpenSpecimen! Contributions and feedback are always welcome.
