# Next.js with Supabase

This is a Next.js application with Supabase integration, featuring:
- TypeScript
- Tailwind CSS
- Cookie-based Authentication
- App Router

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up your environment variables:
   - Copy `.env.example` to `.env.local`
   - Add your Supabase project URL and anon key

4. Run the development server:
   ```bash
   npm run dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser

## Features

- 🔐 Authentication with Supabase
- 🎨 Styled with Tailwind CSS
- 📱 Responsive design
- 🔍 TypeScript for better development experience
- 🚀 Next.js App Router

## Project Structure

```
src/
├── app/              # App Router pages
├── components/       # React components
├── lib/             # Utility functions
└── types/           # TypeScript type definitions
```

## Environment Variables

Create a `.env.local` file with the following variables:
```
NEXT_PUBLIC_SUPABASE_URL=your-project-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-anon-key
```

## Learn More

- [Next.js Documentation](https://nextjs.org/docs)
- [Supabase Documentation](https://supabase.com/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
