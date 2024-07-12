First, run the development server:
Creating a real-time crypto price tracker with Next.js, TypeScript, and a live crypto API involves initializing the project, installing dependencies like Axios, and creating utility files for API calls and WebSocket connections. The React component, designed to display live crypto prices, fetches initial data and subscribes to real-time updates via WebSocket. Integration into the main page completes the setup. This structured approach ensures a modular and maintainable architecture for your real-time crypto price tracker web application, providing a solid foundation for future enhancements.
```bash
npm run dev

```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.