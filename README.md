# Invoice Builder

An invoice and quotation builder desktop application designed for small businesses and freelancers. 

## Features

- **Invoices & Quotes**: Create, manage, and export invoices/quotes.
- **PDF Export**: Generate high-quality PDFs with customizable styles and logos.
- **Local Database**: Stores all data locally using SQLite or PostgreSQL.
- **Modern UI**: Intuitive sidebar navigation, drag-and-drop support, signature canvas, and multi-language support.

## Tech Stack

- **Frontend**: React, Vite, Redux Toolkit, Material UI (MUI)
- **Backend / Desktop**: Electron, Express, SQLite3 / pg (PostgreSQL)

## Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Kashu-aka-lala/Invoice_builder.git
   cd Invoice_builder
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

### Development

Run the application in development mode (spawns both the frontend watch servers and the Electron desktop window):
```bash
npm run dev
```

### Packaging & Release

To package the application for your current operating system (e.g., Windows x64):
```bash
npm run package
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
