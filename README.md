# E-Commerce Platform

A modern e-commerce platform built with Next.js, TypeScript, and Tailwind CSS.

## Getting Started

1. Clone the repository
2. Install dependencies: `npm install`
3. Run the development server: `npm run dev`

## Project Structure

```
├── .github/                    # GitHub workflows and templates
│   ├── workflows/             # CI/CD workflows
│   └── ISSUE_TEMPLATE/        # Issue templates
├── .husky/                    # Git hooks
├── public/                    # Static files
│   ├── images/                # Global images
│   ├── icons/                 # SVG icons
│   └── fonts/                 # Custom fonts
├── src/
│   ├── app/                   # App Router
│   │   ├── (auth)/            # Authentication routes
│   │   ├── (dashboard)/       # Dashboard routes
│   │   ├── (marketing)/       # Marketing pages
│   │   ├── api/               # API routes
│   │   ├── cart/              # Shopping cart
│   │   ├── checkout/          # Checkout process
│   │   ├── products/          # Product pages
│   │   └── ...
│   │
│   ├── components/            # Reusable components
│   │   ├── ui/                # Shadcn/ui components
│   │   ├── cart/              # Cart components
│   │   ├── checkout/          # Checkout components
│   │   ├── common/            # Common components
│   │   ├── layout/            # Layout components
│   │   ├── products/          # Product components
│   │   └── ...
│   │
│   ├── config/                # App configuration
│   ├── constants/             # App constants
│   ├── context/               # React context providers
│   ├── hooks/                 # Custom React hooks
│   ├── lib/                   # Utility functions
│   ├── middleware.ts          # Next.js middleware
│   ├── providers/             # Component providers
│   ├── server/                # Server-only utilities
│   ├── services/              # API services
│   ├── store/                 # State management
│   ├── styles/                # Global styles
│   ├── types/                 # TypeScript types
│   └── utils/                 # Utility functions
│
├── .env.local                 # Environment variables
├── .eslintrc.json             # ESLint config
├── .gitignore                 # Git ignore file
├── next.config.js             # Next.js config
├── package.json               # Project dependencies
├── postcss.config.js          # PostCSS config
├── tailwind.config.js         # Tailwind CSS config
└── tsconfig.json              # TypeScript config
```

## Development

- Use feature branches for new features
- Follow the commit message convention
- Run tests before pushing
- Create PRs for code review

## Code Style

- Follow the project's ESLint and Prettier configuration
- Write meaningful commit messages
- Document complex logic with comments
