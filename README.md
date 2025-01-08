# SVGEdit App

This is a [Tauri](https://tauri.app/)-based version of [SVGEdit](https://github.com/SVG-Edit/svgedit), a fast, web-based, JavaScript-driven SVG drawing editor.

## Overview

SVGEdit app allows you to run SVGEdit as a standalone desktop application without needing to install additional software or rely on a web browser. It combines the power of Tauri for lightweight, secure, and performant desktop applications with the rich feature set of SVGEdit for creating and editing SVG files.

## Features

- **Install**: Run SVGEdit as a standalone application on Windows, macOS, and Linux.
- **Lightweight**: Built with Tauri, ensuring minimal resource usage and fast performance.
- **Full SVGEdit Functionality**: Enjoy all features of SVGEdit, including drawing, editing, and exporting SVG files.

## Installation

You can find an executable version at [releases](https://github.com/brenoepics/svgedit-app/releases/latest)

## Building Locally

### Prerequisites

- [Node.js](https://nodejs.org/) (for building the project)
- [Rust](https://www.rust-lang.org/tools/install) (for building the Tauri backend)

### Building the Application

1. **Clone the Repository**

   ```sh
   git clone https://github.com/brenoepics/svgedit-app.git
   cd svgedit-app
   ```

2. **Install Dependencies**

   ```sh
   npm install
   ```

3. **Build the Application**

   ```sh
   npm run tauri build
   ```

4. **Run the Application**

   ```sh
   npm run tauri dev
   ```

## Usage

After building and running the application, the SVGEdit interface will appear in a standalone window. You can start creating and editing SVG files just as you would in the web-based version of SVGEdit.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch with your feature or bugfix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Open a pull request to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

This project is based on the [SVGEdit](https://github.com/SVG-Edit/svgedit) project. Full credit goes to the original authors and contributors of SVGEdit.

## Links

- [SVGEdit GitHub Repository](https://github.com/SVG-Edit/svgedit)
- [Tauri](https://tauri.app/)
