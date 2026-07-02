

# The Illusion of Smoothness: A History of Differentiability
T
his is an elegant single-page technical history website built using Quarto and deployed via GitHub Pages. The article explores the historical intuition-shattering conflict between "Differentiability" and "Continuity," focusing on how the world moved from the physical intuitions of Newton and Leibniz to Karl Weierstrass's shocking discovery of a function that is "continuous everywhere, but differentiable nowhere."

## 🚀 Project Highlights

<div align="center">
  <img src="Picture4.png" width="90%" alt="Leibniz's calculus manuscript showing early differential notation">
  <br>
  <p><em>Leibniz's original calculus manuscript, beautifully centered and scaled.</em></p>
</div>

Where History Meets Mathematics: A vivid retelling of the intellectual clashes among calculus masters from the 17th to the 19th centuries.

- **Modern Quarto Architecture:** Features built-in automatic cross-referencing, flawless LaTeX formula rendering, and a responsive floating Table of Contents (TOC).
- **Gallery-Grade Layouts:** Includes rare portraits and historical manuscripts of Galileo, Kepler, and Leibniz, organized beautifully using symmetrical dual-column layouts (layout-ncol=2).
- **One-Click Automated Deployment:** Seamlessly hosted on GitHub Pages via quarto publish gh-pages.

## 🛠️ Local Development & Preview Guide

If you want to modify, run, or preview this project locally on your Mac, please make sure your environment is properly configured.
1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
cd YOUR_REPOSITORY_NAME
```
2. Install Underlying Dependencies (macOS)
Ensure you have the Quarto CLI installed, along with Jupyter and PyYAML in your Python environment (bypassing the macOS PEP 668 environment protection):
```bash
Install Quarto via Homebrew
brew install --cask quarto
Install Python dependencies globally by safely bypassing system restrictions
python3 -m pip install jupyter pyyaml --break-system-packages
```
3. Preview in VS Code

Open this project folder in VS Code.
Install the official Quarto extension.
Open the differentiability.qmd file and click the Preview button in the top 
right corner of the editor (or use the shortcut Cmd + Shift + K).

4. Terminal Live Preview Command
```bash
quarto preview differentiability.qmd
```
## 🌐 Deployment & Publishing
This project is pre-configured to be distributed via GitHub Pages. Whenever you make updates to the .qmd file and want to publish them online, just run the following command in your local terminal:
```bash
quarto publish gh-pages differentiability.qmd
```
Quarto will automatically compile the source files, handle the hidden production 
branch (gh-pages), and push the latest static site directly to your GitHub repository.

## 📂 Directory Structure
```text
├── differentiability.qmd     # Core Quarto manuscript (Markdown evolved)
├── picture1.jpg              # Portrait of Galileo
├── picture2.jpg              # Portrait of Kepler
├── picture3.jpg              # Portrait of Leibniz
├── picture4.jpg              # Leibniz's original calculus manuscript
├── README.md                 # Project documentation
└── LICENSE                   # Open-source license (MIT)
```

## 📜 License
This project is open-source and licensed under the MIT License. You are free to copy, modify, distribute, or use it for commercial purposes.