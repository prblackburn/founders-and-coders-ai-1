# Remix Hello World - Founders and Coders Pre-Registration Task

This is a simple Remix application that displays "Hello World" when run. This project was created as a pre-registration task required for attendance/participation at the Founders and Coders event.

## Event Information

This task is required for the Founders and Coders event. For full event details, visit: https://lu.ma/scdosp89

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm

### Installation

1. Clone this repository
2. Install dependencies:
   ```bash
   npm install
   ```

### Development

To start the development server:

```bash
npm run dev
```

The app will be available at http://localhost:3000

### Production

To build for production:

```bash
npm run build
```

To start the production server:

```bash
npm start
```

### Other Commands

- `npm run typecheck` - Run TypeScript type checking

## Project Structure

- `app/` - Contains the Remix application code
  - `routes/_index.tsx` - Main route that displays "Hello World"
  - `root.tsx` - Root component with HTML structure
  - `entry.client.tsx` - Client-side entry point
  - `entry.server.tsx` - Server-side entry point
- `package.json` - Project dependencies and scripts
- `vite.config.ts` - Vite configuration
- `tsconfig.json` - TypeScript configuration

## Technologies Used

- [Remix](https://remix.run/) - Full-stack web framework
- [React](https://reactjs.org/) - UI library
- [TypeScript](https://www.typescriptlang.org/) - Type-safe JavaScript
- [Vite](https://vitejs.dev/) - Build tool
