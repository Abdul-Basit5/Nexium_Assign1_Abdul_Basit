# Quote Generator Application

A modern, responsive web application that generates inspiring quotes based on user-selected topics. Built with React, TypeScript, Express.js, and styled with shadcn/ui components.

## Features

- **Topic-based Quote Generation**: Enter any topic to get 3 curated quotes
- **258+ Curated Quotes**: Hand-picked quotes from renowned authors across 9 categories
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean interface built with shadcn/ui components and Tailwind CSS
- **Share Functionality**: Share quotes via native sharing or copy to clipboard
- **Favorite System**: Mark quotes as favorites with interactive heart buttons
- **Popular Categories**: Quick access buttons for common topics
- **Lightning Fast**: Local storage for instant quote retrieval

## Categories

- Life
- Success
- Motivation
- Love
- Wisdom
- Happiness
- Friendship
- Leadership

## Technology Stack

### Frontend
- React 18 with TypeScript
- Vite for build tooling
- Wouter for routing
- TanStack Query for state management
- shadcn/ui components with Radix UI
- Tailwind CSS for styling
- Lucide React for icons

### Backend
- Node.js with Express.js
- TypeScript
- In-memory storage with Drizzle ORM schema
- RESTful API endpoints
- Zod for validation

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd quote-generator
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:5000`

## API Endpoints

- `GET /api/quotes/:category` - Get quotes by category
- `GET /api/categories` - Get all available categories
- `GET /api/quotes?q={query}` - Search quotes by text content

## Project Structure

```
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Page components
│   │   ├── lib/            # Utility functions
│   │   └── hooks/          # Custom React hooks
├── server/                 # Backend Express application
│   ├── data/               # Quote data
│   ├── routes.ts           # API routes
│   └── storage.ts          # Data storage interface
├── shared/                 # Shared types and schemas
└── components.json         # shadcn/ui configuration
```

## Development

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run check` - TypeScript type checking

## Deployment

The application is configured for easy deployment on Replit or similar platforms. The production build serves static files and API routes from the same Express server.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).