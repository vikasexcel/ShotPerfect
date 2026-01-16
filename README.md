# ShotPerfect

![ShotPerfect Logo](path/to/logo.png) <!-- Replace with actual logo path -->

## Introduction

ShotPerfect is a powerful desktop application designed to enhance your screenshot experience. Built with modern web technologies, it leverages the capabilities of Tauri for a lightweight and efficient user interface. The application integrates various features to streamline the process of capturing, editing, and managing screenshots.

## Key Features

- **Screenshot Capture**: Easily capture screenshots with customizable options.
- **Image Editing**: Basic editing tools to annotate and modify screenshots.
- **Global Shortcuts**: Set up global keyboard shortcuts for quick access.
- **Cross-Platform Support**: Runs seamlessly on Windows, macOS, and Linux.
- **OCR Integration**: Utilize Tesseract.js for optical character recognition.
- **User-Friendly Interface**: Built with React and styled using Tailwind CSS for a modern look.

## Folder Structure

The project follows a structured folder organization for better maintainability:

```
.
├── .git                  # Git version control files
├── .github               # GitHub-specific files (e.g., issue templates)
├── .gitignore            # Files and directories to ignore in Git
├── .vscode               # Visual Studio Code settings
├── AGENTS.md            # Documentation for agents
├── CHANGELOG.md          # Change log for tracking updates
├── CODE_OF_CONDUCT.md    # Code of conduct for contributors
├── CONTRIBUTING.md       # Guidelines for contributing to the project
├── LICENSE               # License information
├── bettershot-landing    # Landing page assets
├── index.html            # Main HTML file
├── package.json          # Project metadata and dependencies
├── pnpm-lock.yaml        # Lock file for pnpm package manager
├── postcss.config.js     # PostCSS configuration
├── public                # Public assets
├── scripts               # Custom scripts
├── src                   # Source code for the application
│   ├── components        # React components
│   ├── hooks             # Custom React hooks
│   └── utils             # Utility functions
├── src-tauri             # Tauri-specific code
│   ├── Cargo.toml        # Rust package configuration
│   └── src               # Rust source code
├── tsconfig.json         # TypeScript configuration
├── tsconfig.node.json    # Node-specific TypeScript configuration
├── vite.config.ts        # Vite configuration
└── vitest.config.ts      # Vitest configuration
```

## Installation & Setup

To get started with ShotPerfect, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/vikasexcel/ShotPerfect.git
   ```

2. Navigate to the project directory:
   ```bash
   cd ShotPerfect
   ```

3. Install the dependencies using pnpm:
   ```bash
   pnpm install
   ```

4. Run the development server:
   ```bash
   pnpm dev
   ```

## Usage

Once the application is running, you can use the following commands:

- **Capture Screenshot**: Use the configured global shortcut to capture a screenshot.
- **Edit Screenshot**: Open the screenshot in the editor to annotate or modify it.
- **Access Settings**: Customize your preferences through the settings menu.

For testing, you can run:
```bash
pnpm test
```
To watch for changes:
```bash
pnpm test:watch
```
For coverage reports:
```bash
pnpm test:coverage
```

Explore the application and enjoy a seamless screenshot experience!