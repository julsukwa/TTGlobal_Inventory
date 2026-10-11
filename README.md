# TT Global Inventory System — Frontend

Frontend for the TT Global Inventory System, a local intranet inventory management application.

## Tech Stack
- React 19 + TypeScript
- Vite
- React Router v7
- Scoped CSS

## Getting Started

### Install dependencies
npm install

### Development
npm run dev

Runs on http://localhost:5173

### Environment Variables
Create a .env.development file:
VITE_API_URL=http://localhost:3000/api

## API Integration
All API calls go through src/services/api.ts.
See API_DOCUMENTATION.md for the full list of endpoints the backend must implement.
