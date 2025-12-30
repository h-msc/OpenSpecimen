![Status](https://img.shields.io/badge/status-active-brightgreen)
[![Demo](https://img.shields.io/badge/demo-live-blue)](https://h-msc.github.io/OpenSpecimen/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Release](https://img.shields.io/github/v/release/h-msc/OpenSpecimen)](https://github.com/h-msc/OpenSpecimen/releases)
[![GitHub stars](https://img.shields.io/github/stars/h-msc/OpenSpecimen)](https://github.com/h-msc/OpenSpecimen/stargazers)
![HTML](https://img.shields.io/badge/html-vanilla-orange)
![CSS](https://img.shields.io/badge/css-modern-blue)
![JavaScript](https://img.shields.io/badge/javascript-vanilla-yellow)

# OpenSpecimen

**OpenSpecimen** is an open-source, self-contained website template for creating interactive type specimens on the web. It’s designed for designers, type foundries, and developers who want a clear, modern way to showcase fonts—especially variable fonts—without a heavy framework.

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

Check out the live demo here: [OpenSpecimen Demo](https://h-msc.github.io/OpenSpecimen/)

Current typeface being displayed by default is [Roboto](https://fonts.google.com/specimen/Roboto) by Christian Robertson.

![Demo Screenshot](https://user-images.githubusercontent.com/yourusername/demo-screenshot.png)  
*Replace with an actual screenshot or GIF showing your interactive tester and glyph grid.*

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

