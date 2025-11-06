# view-transition-vanilla

A lightweight, vanilla JavaScript project showcasing the View Transitions API with modern web standards.

## Overview

This project is a minimal setup using **Vite** (with Rolldown) to demonstrate and experiment with the CSS View Transitions API. It provides a clean foundation for building smooth page transitions without any framework overhead.

## Features

- **View Transitions API** - Smooth navigation transitions with CSS animations
- **Vanilla JavaScript** - No framework dependencies, just plain ES modules
- **Fast Build Tool** - Powered by Vite with Rolldown for optimized development and production builds
- **Code Quality** - Integrated with Biome for linting and formatting

## Tech Stack

- **Build Tool**: Vite 7.1.14 (with Rolldown)
- **Package Manager**: pnpm 9.5.0
- **Linter/Formatter**: Biome 1.9.4
- **Language**: Vanilla JavaScript (ES modules)

## Project Structure

```
view-transition-vanilla/
├── index.html          # Main HTML entry point
├── src/
│   ├── main.js        # Entry point JavaScript file
│   └── style.css      # Global styles with View Transitions configuration
├── package.json       # Project dependencies and scripts
├── biome.json         # Biome configuration for code quality
└── vite.config.js     # Vite build configuration (if exists)
```

## Getting Started

### Prerequisites

- Node.js (v14+)
- pnpm 9.5.0 or higher

### Installation

```bash
# Install dependencies
pnpm install
```

### Development

```bash
# Start the development server
pnpm dev
```

The application will be available at `http://localhost:5173` (or the port displayed in the terminal).

### Build

```bash
# Create production build
pnpm build
```

Output will be generated in the `dist/` directory.

### Preview

```bash
# Preview the production build locally
pnpm preview
```

## Code Quality

This project uses **Biome 1.9.4** for automated code formatting and linting.

### Biome Configuration

- **Formatter**: Enabled with tab indentation
- **Linter**: Enabled with recommended rules
- **Imports**: Auto-organized
- **JavaScript**: Double quotes for consistency

### Running Biome

```bash
# Lint and format code
pnpm biome format --write .
pnpm biome lint .
```

## View Transitions API

The project includes CSS configuration for the View Transitions API:

```css
@view-transition {
  navigation: auto;
}
```

This enables automatic transitions during page navigation. Learn more about the [View Transitions API](https://developer.mozilla.org/en-US/docs/Web/API/View_Transitions_API).

## Browser Support

View Transitions API support varies by browser. Check [caniuse.com](https://caniuse.com/view-transitions) for current support status.

## License

This project is private and not intended for public distribution.
