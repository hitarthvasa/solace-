# Solace

A multi-agent mental wellness app. *Therapy can be expensive, but sometimes presence itself matters.*

Solace (earlier called Echo) is a calm place to check in with yourself, find support and build small daily habits.

> Solace is a supportive tool, not a replacement for professional mental health care. If you are in crisis, please contact a local helpline or someone you trust.

<!-- Add a screenshot or short GIF of the app here: ![Solace dashboard](screenshots/dashboard.png) -->

## Features

- **Sign in** with authentication
- **Dashboard and profile**
- **Find Someone**, to connect with support
- **Resources and insights**
- **Chat agent** to talk things through
- **Self-practice tools:** meditation timer, breathing exercises, soothing sounds, journaling, Gita reading and random quotes

## Design approach

Calm, realistic and human. It is meant to feel like a real, gentle product, not an "AI app", so it avoids anything too pink, childish or full of emoji.

## Built with

- [Next.js](https://nextjs.org/) (App Router)
- [Supabase](https://supabase.com/) for authentication and data
- [Tailwind CSS](https://tailwindcss.com/) and [shadcn/ui](https://ui.shadcn.com/)
- [Framer Motion](https://www.framer.com/motion/) for animation
- [Lucide](https://lucide.dev/) icons

## Run it locally

```bash
git clone https://github.com/hitarthvasa/solace-.git
cd solace-
npm install
```

Create a file called `.env.local` in the project folder and add your own Supabase project details:

```
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key
```

Then start it:

```bash
npm run dev
```

Open http://localhost:3000. Never commit your `.env.local` file.

## Ideas for next

- Daily quote reminders
- A focus mode
- Mood-based colour themes
- An audio-call agent

## Author

Built by [Hitarth Vasa](https://github.com/hitarthvasa).
