# PharmaTech

PharmaTech is a modern, cross-platform desktop application built with Tauri, designed to streamline pharmaceutical management processes.

## Features

- Cross-platform compatibility (Windows, macOS, Linux)
- Efficient and lightweight desktop application
- Modern user interface

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or later)
- [Rust](https://www.rust-lang.org/) (v1.77.2 or later)
- [Tauri CLI](https://tauri.app/v1/api/cli/)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/pharmatech.git
   cd pharmatech
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Run the development server:

   ```sh
   npm run tauri dev
   ```

### Building for Production

To build the application for production, follow these steps:

1. Ensure you have met all the prerequisites mentioned in the "Getting Started" section.

2. Open a terminal and navigate to the project root directory.

3. Run the following command to build the production-ready application:

   ```sh
   npm run tauri build
   ```

4. Once the build process is complete, you can find the compiled binaries in the `src-tauri/target/release` directory.

5. The exact location and format of the output will depend on your operating system:
   - Windows: Look for `pharmatech.exe`
   - macOS: Look for `pharmatech.app`
   - Linux: Look for `pharmatech`

6. You can now distribute the built application to users on the respective platforms.

Note: Make sure to test the built application thoroughly before distribution to ensure all features are working as expected in the production environment.
