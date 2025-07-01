# Tria AI Chat Application

A React + TypeScript + Vite application featuring an AI chat interface with Leo and Max models.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/At41rv1/tria-ai-chat-new.git
   cd tria-ai-chat-new
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure API keys:
   - Copy the example configuration file:
     ```bash
     cp src/config/api-keys.example.ts src/config/api-keys.ts
     ```
   - Edit `src/config/api-keys.ts` and replace the placeholder API keys with your actual Groq API keys:
     ```typescript
     export const API_KEYS = {
       LEO: 'your_leo_api_key_here',  // Replace with your Leo API key
       MAX: 'your_max_api_key_here'   // Replace with your Max API key
     };
     ```

## Development

Run the development server:
```bash
npm run dev
```

The server will start on http://localhost:8000 (or next available port)

## Preview

Run the preview server:
```bash
npm run preview
```

## Features

- Interactive chat interface with two AI personalities:
  - Leo: Friendly and conversational
  - Max: Witty and humorous
- Real-time AI responses using Groq API
- Responsive design with Tailwind CSS
- TypeScript for enhanced type safety
- Fast development with Vite
- Clean and modern UI

## Project Structure

- `src/pages/Chat.tsx`: Main chat interface component
- `src/config/api-keys.ts`: API key configuration (create from example)
- `src/components/`: Reusable UI components
- `src/contexts/`: React context providers
- `src/hooks/`: Custom React hooks

## Security Note

The `api-keys.ts` file is excluded from version control for security. Always keep your API keys private and never commit them to the repository.
