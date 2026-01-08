# URL Diff Tool

A POC for comparing and analyzing differences between two URLs. Built with React, TypeScript, and Vite. It parses the URL components (protocol, host, path, and query parameters) and displays them in a table, making it easy to identify differences between URLs.

## Features

- Parse and display URL components in a structured table
- Compare two URLs side-by-side
- Highlight query parameters on separate rows for easy comparison
- Support for complex query strings with multiple parameters

## Environment Requirements

- **Node.js**: v18 or higher
- **npm**: v9 or higher

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```
   This command automatically downloads and installs everything the project needs to run.

2. Run the development server:
   ```bash
   npm run dev
   ```

3. Open your browser to the URL shown in the terminal (typically `http://localhost:5173`)

## Build

To build for production:
```bash
npm run build
```

## Project Structure

- `src/components/` - React components
- `src/utils/` - Utility functions for URL parsing and diffing
- `src/styles/` - Component styling
