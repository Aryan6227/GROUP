
# Map Generator

Create procedural American-style cities.

![Map Generator Screen Shot](mapgenerator(GROUP)/docs/images/screenshot.png)

## Overview

Map Generator is a tool for procedurally generating city maps and 3D models, inspired by American-style urban layouts. It supports both automated and manual workflows, allowing users to control each stage of the map generation process for customized results.

### Key Features

- **Procedural Generation:** Automatically create realistic city maps with roads, buildings, parks, and water features.
- **Customizable Output:** Control generation parameters for finer control over the map's appearance and structure.
- **Multiple Export Formats:** Download generated cities as `.png`, `.svg`, or `.stl` files. STL exports are provided as a zip containing separate files for different map components.
- **Drawing Styles:** Choose from several visual styles, including color themes similar to Google or Apple Maps, or a hand-drawn sketch look.
- **3D Models:** Export 3D models for use in other applications or for 3D printing.

## Built With

- [Typescript](https://www.typescriptlang.org/)
- [Gulp](https://gulpjs.com/)

## Getting Started

Follow these steps to set up Map Generator locally:

### Prerequisites

- [Node.js](https://nodejs.org/) and npm
- [Gulp CLI](https://gulpjs.com/)

Install prerequisites:
```sh
npm install npm@latest -g
npm install --global gulp-cli
```

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/probabletrain/mapgenerator.git
   ```
2. Install dependencies:
   ```sh
   cd mapgenerator
   npm install
   ```
3. Build the project:
   ```
   gulp
   ```
   This will watch for changes to TypeScript files. If you edit HTML or CSS, rerun this command.

4. Open `dist/index.html` in your web browser to view the generator.

## Usage

- Visit the [documentation](https://maps.probabletrain.com) for detailed usage instructions and examples.
- Use the generator to create city maps, adjust parameters, and export your results.

## Project Structure

- `src/` — Main source code (TypeScript, HTML, CSS)
- `docs/` — Documentation and images
- `dist/` — Build output (after running Gulp)
- `COPYING`, `COPYING.LESSER` — License files

## License

Distributed under the LGPL-3.0 License. See `COPYING` and `COPYING.LESSER` for more information.
