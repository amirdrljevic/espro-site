# ESPRO web page 🦸

This project transforms a design from Adobe XD file into a functional web page using HTML, CSS, and JS.

![ESPRO Logo](app/assets/images/ESPRO Logo.svg)

## Table of Contents

- [Features](#features)
- [Setup Instructions](#setup-instructions)
- [Styling Guide](#styling-guide)

## Features

- **Several sections of the page**: There are header, hero, best seller and life coffee sections
- **HTML**: The design is reflecting the XD design
- **CSS**: SCSS is used to separate the styling into more manageable pieces

## Setup Instructions

1. **Clone the repository**:

   ```bash
   git clone https://github.com/amirdrljevic/espro-site.git
   cd espro-site
   ```

2. **Install dependencies**:

   Make sure you have Ruby and Rails 7 installed. Then,

   ```bash
   bundle install
   ```

3. **Start the Rails server**:

   ```bash
   rails server
   ```

   Visit `http://localhost:3000` in your browser.

## Styling Guide

Styling is managed through SCSS, ensuring a modern look and feel to the application. The BEM methodology was used along with variables for consistency.

1. **Variables**: All SCSS variables are defined in `variables.scss`. This includes colors, font sizes, and common margins/paddings.
2. **Custom Styles**: Custom styles can be found in several scss files. This includes component-specific styles and utility classes.

3. **Using Bootstrap**: Bootstrap's grid system and components are used for responsiveness.
