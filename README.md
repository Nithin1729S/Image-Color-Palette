# Image Color Palette

## Overview
**Image Color Palette** is a Next.js-based web application that allows users to extract color palettes from uploaded images. Users can easily upload an image, view its color composition, and copy color values in different formats (RGB, HEX, HSL).

## Screenshots

![image](https://github.com/user-attachments/assets/9441d427-b004-412b-995c-6e5a6b643994)

![image](https://github.com/user-attachments/assets/a59b44e2-c0db-4317-a579-e929e1664ef7)

## Features
- **Image Upload**: Drag and drop or click to upload an image.
- **Color Extraction**: Automatically extracts dominant colors from the uploaded image.
- **Copy Colors**: Copy color values in RGB, HEX, and HSL formats with a single click.
- **Download Palette**: Save the extracted color palette for later use.

## Tech Stack
- **Frontend**: Next.js (React, TypeScript, Tailwind CSS)
- **State Management**: React Context API
- **Libraries Used**:
  - `next-themes` for dark mode support
  - `lucide-react` for icons
  - `@radix-ui/react-dialog` for modals
  - `next/font/google` for fonts
- **Styling**: Tailwind CSS with custom themes

## Installation

### Prerequisites
Ensure you have **Node.js (>= 16)** and **npm (or yarn)** installed.

### Clone the Repository
```sh
git clone https://github.com/Nithin1729S/Image-Color-Palette
cd Image-Color-Palette
```
### Install Dependencies

```sh
npm install
```

### Run the dev server
```sh
npm run dev
```

Open http://localhost:3000 in your browser.




