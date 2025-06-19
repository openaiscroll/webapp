# OpenAIScroll Web App

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A platform for sharing and exploring AI chat conversations with a focus on code sharing and discovery.

## Features

- 🚀 View and share AI chat conversations
- 📱 Mobile-first responsive design
- 📝 Code blocks with syntax highlighting
- 🔍 Search functionality
- ⚡ Fast and performant

## Getting Started

### Prerequisites

- Node.js 18 or later
- pnpm
- MongoDB Atlas account

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/openaiscroll/webapp.git
   cd webapp
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env.local
   # Edit .env.local with your configuration
   ```

4. Run the development server:
   ```bash
   pnpm dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Development

- `pnpm dev` - Start development server
- `pnpm build` - Build for production
- `pnpm start` - Start production server
- `pnpm lint` - Run ESLint
- `pnpm test` - Run tests

## Contributing

Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
