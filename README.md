# WordPress React Starter Theme

A modern WordPress theme starter that integrates React components using Vite for a fast development experience.

## Features

- ⚡️ **Blazing Fast Development** - Vite-powered build system with hot module replacement
- ⚛️ **React Integration** - Build modern UI components with React and TypeScript
- 🎨 **CSS Support** - Built-in CSS support with PostCSS processing
- 🧩 **WordPress Compatibility** - Standard theme structure with modern enhancements
- 📦 **TypeScript Support** - Type-safe development environment

## Requirements

- WordPress 6.0+
- PHP 7.4+
- Node.js 16+
- npm 8+

## Installation

1. Clone this repository into your WordPress themes directory:
```bash
cd wp-content/themes
git clone https://github.com/tuanha1305/wordpress-react-wp.git
```

2. Install dependencies:
```bash
cd wordpress-react-wp
npm install
```

3. Build the theme:
```bash
npm run build
```

4. Activate the theme in WordPress admin.

## Development

Start the development server:
```bash
npm run dev
```

This will:
- Start Vite development server
- Watch for changes in React components
- Enable hot module replacement

## Project Structure

```
.
├── app/                  # WordPress PHP templates
├── src/                  # React components
│   ├── App.tsx           # Main React component
│   ├── main.tsx          # React entry point
│   └── assets/           # Static assets
├── style.css             # Theme styles
├── vite.config.ts        # Vite configuration
└── package.json          # Project dependencies
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a pull request

## License

This project is licensed under the MIT License.
