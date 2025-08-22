# Image Generation App
This project is a Next.js-based web application that allows users to generate AI-powered images by providing text prompts. The app interfaces with the GPT-4 Image Generation API to create unique images based on user input. The application features a clean UI with state management, custom hooks, and API integration, while following React best practices.

## Learning Objectives
By completing this project, you will:

- Understand and implement React state management using useState
- Create and utilize custom React hooks
- Work with environment variables for API key management
- Implement API routes in Next.js applications
- Develop reusable React components
- Manage application state across multiple components
- Implement responsive UI design with Tailwind CSS
- Handle asynchronous operations in React

## Requirements
- Node.js (v14 or later)
- Next.js (v13 or later)
- React (v18 or later)
- TypeScript
- Tailwind CSS
- `GPT-4 API` key (from RapidAPI)
- Modern web browser

## Project Structure

```
├── components/
│   ├── common/
│   │   └── ImageCard.tsx
│   └── layouts/
│       ├── Footer.tsx
│       ├── Header.tsx
│       └── Layout.tsx
├── constants/
│   └── index.ts
├── hooks/
│   └── useFetchData.ts
├── interfaces/
│   └── index.ts
├── pages/
│   ├── api/
│   │   └── generate-image.ts
│   ├── _app.tsx
│   └── index.tsx
├── public/
└── styles/
    └── globals.css
```

## Key Features

1. Image Generation

- Text prompt input
- API integration with GPT-4 Image Generation
- Loading states during generation

2. Image Gallery

- History of generated images
- Thumbnail previews
- Click to view full image

3. Responsive UI

- Works on mobile and desktop
- Clean, modern design
- Intuitive navigation
  
4. Custom Hooks

- Reusable data fetching logic
- State management abstraction
- Error handling

Auther `George Okumu`
