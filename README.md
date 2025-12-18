# Trisolve - Next.js Template

Modern Next.js 16 template with TypeScript, Tailwind CSS v4, ESLint, Prettier, and React Compiler pre-configured. Ready to start coding immediately after cloning.

## 🚀 Features

- ⚡ **Next.js 16** - Latest version with App Router
- 🔷 **TypeScript** - Full type safety
- 🎨 **Tailwind CSS v4** - Latest styling framework
- 🔧 **ESLint + Prettier** - Code quality and formatting
- ⚛️ **React 19.2.3** - Latest stable React with security patches
- 🚀 **React Compiler** - Automatic optimizations enabled
- 📦 **Absolute Imports** - Clean imports with `@/` alias
- 🌙 **Dark Mode Ready** - Pre-configured dark mode support

## 📋 Prerequisites

- Node.js 18.x or higher
- npm, yarn, pnpm, or bun

## 🛠️ Quick Start

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd trisolve
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables** (optional)
   ```bash
   cp .env.example .env.local
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📜 Available Scripts

| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server on port 3000 |
| `npm run build` | Build production bundle |
| `npm run start` | Start production server |
| `npm run lint` | Run ESLint to check code quality |
| `npm run lint:fix` | Auto-fix ESLint issues |
| `npm run format` | Format code with Prettier |
| `npm run format:check` | Check code formatting |
| `npm run type-check` | Run TypeScript type checking |

## 📁 Project Structure

```
trisolve/
├── public/             # Static files
├── src/
│   └── app/           # Next.js App Router pages
│       ├── Home/      # Home page components
│       ├── globals.css # Global styles
│       ├── layout.tsx # Root layout
│       └── page.tsx   # Homepage
├── .env.example       # Environment variables example
├── .gitignore         # Git ignore rules
├── eslint.config.mjs  # ESLint configuration
├── next.config.ts     # Next.js configuration
├── package.json       # Dependencies and scripts
├── postcss.config.mjs # PostCSS configuration
├── tsconfig.json      # TypeScript configuration
└── README.md          # This file
```

## 🎨 Customization

### Fonts
This template uses [Geist](https://vercel.com/font) font family. To change fonts, edit `src/app/layout.tsx`.

### Metadata
Update site metadata in `src/app/layout.tsx`:
```typescript
export const metadata: Metadata = {
  title: 'Your App Title',
  description: 'Your app description',
}
```

### Styling
- Global styles: `src/app/globals.css`
- Tailwind config: Uses Tailwind v4 CSS configuration

## 🔒 Environment Variables

Create a `.env.local` file in the root directory:

```env
# Add your environment variables here
NEXT_PUBLIC_API_URL=https://api.example.com
```

## 🧪 Code Quality

This template includes:
- **ESLint**: Enforces code quality rules
- **Prettier**: Ensures consistent code formatting
- **TypeScript**: Provides type safety with strict mode enabled

Run checks before committing:
```bash
npm run lint
npm run format:check
npm run type-check
```

## 📦 Building for Production

```bash
npm run build
npm run start
```

## 🚀 Deployment

### Vercel (Recommended)
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

### Other Platforms
This project can be deployed to any platform that supports Next.js:
- Netlify
- AWS Amplify
- Docker
- Node.js server

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [TypeScript Documentation](https://www.typescriptlang.org/docs)

## 💡 Tips

- Use absolute imports: `import Component from '@/app/components/Component'`
- Components in `src/app` are Server Components by default
- Add `'use client'` directive for Client Components
- Environment variables prefixed with `NEXT_PUBLIC_` are exposed to the browser

---

**Happy coding! 🎉**
