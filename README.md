# CodinIT.dev Docs

This repository contains the official documentation for **CodinIT**, an AI-powered full-stack development platform that revolutionizes how developers build applications with local and cloud AI models.

## 🚀 What is CodinIT?

CodinIT is a comprehensive development environment that integrates AI assistance throughout the entire development workflow. It supports 19+ AI providers including OpenAI, Anthropic, Google, DeepSeek, and more, offering:

- **Smart Code Generation**: AI-powered code completion and generation
- **Full-Stack Development**: Built for Node.js full-stack applications
- **Multiple AI Providers**: Connect with your preferred AI models
- **Integrated Tools**: Terminal, file management, and deployment
- **Local Model Support**: Run AI models locally with Ollama and LM Studio
- **Enterprise Security**: Bank-level security and compliance

## 📚 Documentation Structure

This documentation site is built with [Mintlify](https://mintlify.com) and covers:

- **Getting Started**: Quickstart guides and installation
- **Features**: Development tools, AI integration, and workflows
- **Providers**: Configuration for 19+ AI providers
- **Integrations**: Vercel, Netlify, Supabase, and Git
- **MCP Protocol**: Extending capabilities with custom tools
- **Comparisons**: How CodinIT compares to other platforms

## 🛠️ Development Setup

### Prerequisites

- Node.js 18+
- pnpm, npm, or yarn

> **Important**: If you have a package named `mint` and a package named `mintlify` installed, you should uninstall `mintlify`.
>
> 1. Uninstall the old package:
>
>    ```bash
>    npm uninstall -g mintlify
>    ```
>
> 2. Clear your npm cache:
>
>    ```bash
>    npm cache clean --force
>    ```
>
> 3. Reinstall the new package:
>    ```bash
>    npm i -g mint
>    ```

### Local Development

1. **Clone the repository**

   ```bash
   git clone https://github.com/codinit-dev/docs.git
   cd docs
   ```

2. **Install dependencies**

   ```bash
   # Using pnpm (recommended)
   pnpm install

   # Or using npm
   npm install

   # Or using yarn
   yarn install
   ```

3. **Start the development server**

   ```bash
   # Using pnpm
   pnpm dev

   # Or using npm
   npm run dev

   # Or using yarn
   yarn dev
   ```

4. **Open your browser** to `http://localhost:3000`

### Building for Production

```bash
# Build the documentation site
pnpm build

# Preview the production build
pnpm preview
```

## 📝 Contributing

We welcome contributions to improve the documentation! Here's how you can help:

### Content Contributions

1. **Fork** this repository
2. **Create a feature branch**: `git checkout -b feature/your-feature-name`
3. **Make your changes** to the MDX files in the appropriate directories
4. **Test your changes** locally with `pnpm dev`
5. **Commit your changes** following conventional commit format
6. **Push to your fork** and create a **Pull Request**

### Documentation Guidelines

- Use clear, concise language
- Include code examples where helpful
- Follow the existing MDX structure and component usage
- Test all links and ensure they're working
- Use proper heading hierarchy (H1 → H2 → H3)

### File Structure

```
docs/
├── index.mdx                 # Homepage
├── quickstart.mdx           # Getting started guide
├── features/                # Feature documentation
├── providers/               # AI provider guides
├── integrations/            # Third-party integrations
├── essentials/              # Core functionality
├── mcp/                     # MCP protocol docs
├── comparisons/             # Platform comparisons
├── running-models-locally/  # Local AI setup
└── assets/                  # Images, icons, and media
```

## 🔧 Configuration

The documentation is configured through `docs.json`:

- **Theme**: Aspen theme with custom colors
- **Navigation**: Organized into logical tabs and groups
- **SEO**: Optimized for search engines
- **Integrations**: Telemetry and analytics enabled

## 📄 License

This documentation is part of the CodinIT project. See the main project [LICENSE](LICENSE) for details.

## 🌐 Links

- **CodinIT App**: [codinit.dev](https://codinit.dev)
- **Documentation**: [codinit.dev/docs](https://codinit.dev/docs)
- **GitHub Repository**: [github.com/codinit-dev/codinit-dev](https://github.com/codinit-dev/codinit-dev)
- **Download**: [codinit.dev/download](https://codinit.dev/download)
- **Blog**: [codinit.dev/blog](https://codinit.dev/blog)

## 📞 Support

- **Issues**: [GitHub Issues](https://github.com/codinit-dev/codinit-dev/issues)
- **Discussions**: [GitHub Discussions](https://github.com/codinit-dev/codinit-dev/discussions)
- **Community**: Join our Discord community for real-time help
