# DevUtils - Free Developer Tools

Fast, simple, and powerful developer tools. 100% client-side, no data ever sent to servers.

## 🚀 Features

### Available Tools

1. **Epoch Converter** - Convert Unix timestamps with millisecond/microsecond/nanosecond support
2. **JSON Formatter** - Format, minify, sort keys, escape, and validate JSON
3. **Base64 Encoder** - Encode/decode with URL-safe option and size comparison
4. **URL Encoder** - Encode/decode URLs with parser and query string builder
5. **JSON Validator** - Validate JSON syntax with detailed error messages

### Key Features

- ✅ **100% Client-Side** - All processing happens in your browser
- ✅ **Private & Secure** - No data sent to servers
- ✅ **Dark Mode** - Beautiful dark mode with system preference detection
- ✅ **Fast & Responsive** - Optimized performance
- ✅ **Mobile Friendly** - Works great on all devices
- ✅ **Detailed Stats** - See size, depth, structure info for all operations

## 🛠️ Tech Stack

- **Framework**: Next.js 13.5.6 (Static Export)
- **Language**: TypeScript
- **Styling**: Tailwind CSS (Stripe-inspired design system)
- **Testing**: Jest + React Testing Library
- **Hosting**: Vercel (recommended) or any static host

## 📦 Getting Started

### Prerequisites

- Node.js 18.14.0 or higher
- npm 9.4.2 or higher

### Installation

```bash
# Clone the repository
git clone <your-repo-url>
cd tools

# Install dependencies
npm install

# Run development server
npm run dev

# Open http://localhost:3000
```

### Development Commands

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run start    # Start production server (after build)
npm test         # Run tests
npm run lint     # Run ESLint
```

## 🧪 Testing

We maintain high test coverage for all core utilities:

```bash
# Run all tests
npm test

# Run tests with coverage
npm test -- --coverage

# Run tests in watch mode
npm test -- --watch
```

Current coverage: **90%+** for core utilities

See [docs/TESTING.md](./docs/TESTING.md) for detailed testing strategy.

## 🎨 Design System

We use a clean, Stripe-inspired design system:

- **Colors**: GitHub blue (#0969da) primary, minimal accent colors
- **Typography**: System fonts for familiarity and speed
- **Components**: Flat design, subtle shadows, clean cards
- **Dark Mode**: Full support with system preference detection

See [docs/STRIPE_DESIGN_COMPLETE.md](./docs/STRIPE_DESIGN_COMPLETE.md) for details.

## 📁 Project Structure

```
tools/
├── app/                    # Next.js app directory
│   ├── epoch-converter/    # Epoch converter page
│   ├── json-formatter/     # JSON formatter page
│   ├── base64-encode/      # Base64 encoder page
│   ├── url-encode/         # URL encoder page
│   ├── json-validator/     # JSON validator page
│   ├── layout.tsx          # Root layout
│   └── page.tsx            # Homepage
├── components/
│   ├── layout/             # Layout components
│   ├── shared/             # Shared UI components
│   └── tools/              # Tool-specific components
├── lib/
│   └── tools/              # Core utility functions
├── __tests__/              # Jest tests
├── docs/                   # Documentation
└── public/                 # Static assets
```

## 🚀 Deployment

### Deploy to Vercel (Recommended)

1. Push your code to GitHub
2. Import project in Vercel
3. Deploy automatically on every push

See [docs/VERCEL_DEPLOYMENT_GUIDE.md](./docs/VERCEL_DEPLOYMENT_GUIDE.md) for detailed instructions.

### Static Export

This project uses Next.js static export, so you can deploy to any static hosting:

```bash
npm run build
# Output in 'out/' directory
```

Host on: Netlify, Cloudflare Pages, GitHub Pages, or any CDN.

## 📈 SEO Strategy

We optimize for developer tool searches:

- Keyword-rich titles and meta descriptions
- Schema.org markup for tools
- Fast loading times (<2s)
- Mobile-responsive design
- Educational content on each tool page

See [docs/SEO_STRATEGY.md](./docs/SEO_STRATEGY.md) for the complete strategy.

## 🤖 AI & Crawler Policy

This project includes policies for AI systems and web crawlers in `robots.txt` (industry standard):

### `robots.txt`
- Allows all search engine crawlers
- Includes specific User-Agent directives for major AI crawlers:
  - GPTBot (OpenAI GPT/ChatGPT)
  - Google-Extended (Google Gemini/Bard)
  - anthropic-ai (Anthropic Claude)
  - Claude-Web (Claude browsing)
  - CCBot (Common Crawl)
  - cohere-ai, PerplexityBot, Applebot-Extended
- References sitemap for SEO

**AI Content Usage**: We allow AI systems to access and learn from our content with the expectation of attribution. See `docs/AI_CRAWLER_POLICY.md` for details.

File location: `public/robots.txt` → `https://devutils.dev/robots.txt`

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

### Development Workflow

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Add tests for new functionality
5. Ensure tests pass (`npm test`)
6. Commit your changes (`git commit -m 'Add amazing feature'`)
7. Push to the branch (`git push origin feature/amazing-feature`)
8. Open a Pull Request

## 📝 License

This project is open source and available under the MIT License.

## 🔗 Links

- **Documentation**: [docs/](./docs/)
- **Live Demo**: TBD (deploy to get URL)
- **Issues**: GitHub Issues

## 💡 Roadmap

- [ ] Add more tools (Hash Generator, UUID Generator, Regex Tester)
- [ ] Add syntax highlighting for JSON/code
- [ ] Add diff viewer for JSON comparison
- [ ] Add file upload support
- [ ] Add export to file functionality
- [ ] Add keyboard shortcuts
- [ ] Add more detailed error messages
- [ ] Add tutorials/examples for each tool

---

Made with ❤️ for developers
