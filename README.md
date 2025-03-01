# Accountra

A modern, professional desktop accounting application with a beautiful user interface and powerful features.

![Accountra Dashboard](https://via.placeholder.com/1200x800.png?text=Accountra+Dashboard)

## Overview

Accountra is a free, offline-first desktop accounting application that provides professional-grade accounting features with an intuitive, modern interface. It supports double-entry bookkeeping, transaction management, multi-currency support, and comprehensive reporting—all with no subscription fees or cloud dependencies.

## Key Features

- **Complete Double-Entry Accounting**: Proper accounting with hierarchical account structures
- **Transaction Management**: Split transactions across multiple accounts with detailed metadata
- **Multi-Currency Support**: Track assets and liabilities in different currencies
- **Beautiful Dashboard**: Get a quick overview of your financial situation
- **Comprehensive Reporting**: Generate financial reports with customizable parameters
- **Bank Reconciliation**: Match transactions against your bank statements
- **Document Attachment**: Store receipts and other documents with your transactions
- **Offline-First Design**: Your data stays on your computer, no internet required
- **Free and Open Source**: No subscription fees, no cloud requirements

## Installation

### macOS

1. Download the latest release from the [Releases](https://github.com/accountra/accountra/releases) page
2. Open the DMG file and drag Accountra to your Applications folder
3. Open Accountra from your Applications folder

### Windows

1. Download the latest release from the [Releases](https://github.com/accountra/accountra/releases) page
2. Run the installer and follow the on-screen instructions
3. Open Accountra from your Start menu

### Linux

1. Download the latest release from the [Releases](https://github.com/accountra/accountra/releases) page
2. Extract the AppImage file to your preferred location
3. Make the AppImage executable (`chmod +x Accountra-x.x.x.AppImage`)
4. Run the AppImage

## Development

### Prerequisites

- Node.js (v16 or later)
- npm (v7 or later)

### Setup

```bash
# Clone the repository
git clone https://github.com/accountra/accountra.git
cd accountra

# Install dependencies
npm install

# Start development server
npm run dev
```

### Building for Production

```bash
# Build for current platform
npm run build

# Build for specific platforms
npm run build:mac
npm run build:win
npm run build:linux
```

## Project Structure

```
accountra/
├── assets/              # Application assets (icons, images)
├── dist/                # Build output directory
├── node_modules/        # Dependencies
├── src/                 # Source code
│   ├── main/            # Electron main process
│   ├── renderer/        # React frontend code
│   ├── database/        # Database models and operations
│   └── shared/          # Code shared between main and renderer
├── package.json         # Project configuration
└── README.md            # This file
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Credits

Accountra is built using the following technologies:

- [Electron](https://www.electronjs.org/)
- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Material-UI](https://mui.com/)
- [SQLite](https://www.sqlite.org/)

## Contact

Project Link: [https://github.com/accountra/accountra](https://github.com/accountra/accountra)

---

<p align="center">
  Made with ❤️ by the Accountra Team
</p> 
